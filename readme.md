# CPS Lab homepage

## Core

- jekyll 3.9.0
- ruby 2.4.10

## Contributes

### ruby 環境構築

```bash
brew update
brew upgrade ruby-build
rbenv install 2.4.10
```

rbenv は PATH 通すことが必要になる場合もあります
適宜やること！

### 環境構築

```bash
gem install bundler
bundle install
jekyll serve
```

Open [http://localhost:4000](http://localhost:4000)

##### フォルダ内に本リポジトリの環境を収めたい人

```bash
gem install bundler
bundle install --path vendor/bundle
bundle exec jekyll serve
```

### メンバー編集

Edit `./_data/members.yml`

### 記事作成

TODO:
