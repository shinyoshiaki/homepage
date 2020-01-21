[English](README.en.md) | [日本語](README.md) | [简体中文](README.zh_hans.md) |

# みんなでつくろう「おめシスホームページ」！

[![](https://github.com/omegasisters/homepage/workflows/build/badge.svg)](https://github.com/omegasisters/homepage/actions)
[![Percentage of issues still open](http://isitmaintained.com/badge/open/omegasisters/homepage.svg)](http://isitmaintained.com/project/omegasisters/homepage 'Percentage of issues still open')

みんなで作るおめがシスターズのホームページです

https://omegasisters.github.io/homepage

[![](assets/images/ogp.png)](https://omegasisters.github.io/homepage)

## このサイトは何のためにありますか？

本サイトは、「第１回おめシスのホームページをプルリクだけで更新していったらどうなるの？」という、おめがシスターズの企画用サイトです

ユーザー参加型の企画なので、誰でも参加することができます 👏

> おめシスのホームページを Github のプルリクで更新していったらどうなるのか、こっそり検証中です。そのうち動画にします！ https://t.co/rErhv32NNR
>
> &mdash; おめがレイ@バーチャル双子 YouTuber ([@omesis_ray](https://twitter.com/omesis_ray)) [December 23, 2019](https://twitter.com/omesis_ray/status/1209057136992387072?ref_src=twsrc%5Etfw)

## この企画に参加するにはどうすればいいですか？

大きくわけて 3 つの方法があります

- [issue(要望・不具合)](https://github.com/omegasisters/homepage/issues) を立てる・コメントする
- [PR](https://github.com/omegasisters/homepage/pulls) を投げる・レビューする
- Twitter で共有 🎉
- その他、みんなで盛り上げていきましょう 👍

## 企画の結果が出ました！

[【検証】１ヶ月間、プルリクだけでホームページ作ったらどうなるの？](https://youtu.be/5h1NoX3my0s)

## 開発のやり方

### GitHub アカウント

GitHub のアカウントは持っていますか？

なければ[ここ](https://github.com/)で作成することができます。

### yarn の導入方法

[※npm で実行したい場合](documents/environment/npm.md)

※OS 別、公式ドキュメントへのリンク

- [mac OS](https://yarnpkg.com/lang/ja/docs/install/#mac-stable)
- [Windows](https://yarnpkg.com/lang/ja/docs/install/#windows-stable)
- [Linux(Ubuntu/Debian)](https://yarnpkg.com/lang/ja/docs/install/#debian-stable)

### Node.js の導入方法

[こちら](https://nodejs.org/ja/download/)をご確認ください

### パッケージインストール

```
yarn install
```

### ローカルプレビュー

コマンドを実行すると、 http://localhost:8080 にホストされます

```
yarn start
```

### コード整形

```
yarn format
```

### テストコードを実行する

```
yarn test
```

#### Sample Test Case

`__tests__`, `preact` にサンプルテストケースがあります

### 使用されている技術にはどんなものがありますか？

[こちら](./documents/environment/README.md)を確認してください
