# DCS Host Simulator 日本語マニュアル(非公式)

The Vision Council が配っている「DCS Host Simulator」(2.0.6.1)の、日本語の使い方の資料です。
DCS(Data Communication Standard)は、眼鏡レンズの加工所で、ホスト(管理ソフト)と装置(トレーサー・エッジャーなど)がデータをやりとりするための決まりです。DCS Host Simulator は、そのホストの役をして、装置が規格どおりに通信できるかを試すソフトです。

日本語の DCS の情報はとても少ないので、規格を学ぶ人や、装置の通信を試す人の助けになればと思い、まとめました。

## 中身

| ファイル | 内容 |
| --- | --- |
| [manual.md](manual.md) | 日本語マニュアル。画面ごとの項目(英日対照)、使い方の手順、DCS.INI の設定、ログによく出る言葉 |
| [notes.md](notes.md) | 使うときの留意点。試していて気づいた動きと、仕様かもしれない点 |
| [jobs.md](jobs.md) | 付属のサンプルジョブ 51 件の一覧 |
| `images/` | マニュアルの画面の画像(英語版) |

## 入手について

DCS Host Simulator は、The Vision Council のウェブサイトの「[Standards for Communication](https://thevisioncouncil.org/members/standards-communication)」のページにある「Data Communication Standard Simulator Software」から入手できます。The Vision Council の会員でなくても入手して使えることを、2026 年 10 月に The Vision Council に問い合わせて確認しました。

このリポジトリには、DCS Host Simulator の本体や付属のファイルは入っていません。

## お断り

- これは個人が調べて書いた**非公式**の資料です。The Vision Council が作ったり、確かめたりしたものではありません。
- 内容は、DCS Host Simulator 2.0.6.1 を Windows で試した範囲のものです。誤りがあるかもしれません。
- DCS Host Simulator と DCS 規格の著作権は The Vision Council にあります。

## ライセンス

このリポジトリの文章は [MIT ライセンス](LICENSE)です。

ただし、次のものは The Vision Council の著作物で、MIT ライセンスの対象ではありません。使い方を説明するために載せています。

- `images/` の画面の画像
- 文中に引いた、画面・ログ・設定ファイルの英語の文

## 謝辞

問い合わせに丁寧に答えてくださった The Vision Council の皆さまに、心より感謝いたします。
