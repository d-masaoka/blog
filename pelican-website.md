# Pelican + Github Pages で Web にサイト公開

# 要件
- ローカルで記事がかける
- markdown で記事がかける
- 書いた記事をコマンド1つでこうかいできる

# Pelican

```
pip install pelican markdown

```

```
pelican-quickstart
```

```
> Where do you want to create your new web site? [.] .
> What will be the title of this web site? samplesite
> Who will be the author of this web site? lunachevalier
> What will be the default language of this web site? [ja] ja
> Do you want to specify a URL prefix? e.g., https://example.com   (Y/n) n
> Do you want to enable article pagination? (Y/n) Y
> How many articles per page do you want? [10] 10
> What is your time zone? [Europe/Paris] Asia/Tokyo
> Do you want to generate a tasks.py/Makefile to automate generation and publishing? (Y/n) Y
> Do you want to upload your website using FTP? (y/N) n
> Do you want to upload your website using SSH? (y/N) n
> Do you want to upload your website using Dropbox? (y/N) n
> Do you want to upload your website using S3? (y/N) n
> Do you want to upload your website using Rackspace Cloud Files? (y/N) n
> Do you want to upload your website using GitHub Pages? (y/N) y
> Is this your personal page (username.github.io)? (y/N) y
```

## 記事を書く
content 配下に markdown で記事を書く

```
Title: 最初の投稿
Date: 2019-02-24
Category: テスト
Tags: テスト, 投稿
Slug: FirstPost
Authors: lunachevalier
Summary: 簡単にブログ作成

# これで簡単に記事が作成できます

デフォルトだと、こんなデザインで出力されます
```

```
make html
```

```
make serve
```
