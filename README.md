# HEIGHTEN

**HEIGHTEN** は、Mixed Game Poker をブラウザ上で学びながらプレイできる無料の Web トレーナーです。

No-Limit Hold’em の基本を知っているプレイヤーが、8-Game や H.O.R.S.E. などの Mixed Game に進むための橋渡しを目的にしています。

## Play Modes

### TRAINING
以下の8ゲームを、1ゲームずつ練習できます。

- 2-7 Triple Draw
- Limit Hold’em
- Omaha Hi-Lo 8 or Better
- Razz
- Seven Card Stud
- Stud Hi-Lo 8 or Better
- No-Limit Hold’em
- Pot-Limit Omaha

### 8-GAME MIX
8ゲームを6Handずつ、合計48Handプレイします。

1. 2-7 Triple Draw
2. Limit Hold’em
3. Omaha Hi-Lo 8 or Better
4. Razz
5. Seven Card Stud
6. Stud Hi-Lo 8 or Better
7. No-Limit Hold’em
8. Pot-Limit Omaha

### 5-GAME MIX
以下の2種類を収録しています。

- H.O.R.S.E.
- T.O.R.S.E.

Mix Session はブラウザ内に保存され、中断後に「続きから」再開できます。

## Learning Features

HEIGHTEN は、単にPokerをプレイするだけでなく、Mixed Game のルールを理解するための学習機能を備えています。

- Rules & Glossary
- Learning Guide
- Learning Panel
- Action Hint
- Glossary Tooltip
- Draw History
- 4-Color Deck
- Sound Effects

Glossary Tooltip は、No-Limit Hold’em 経験者が Mixed Game で初めて出会いやすい用語を中心に表示します。

## Rules

HEIGHTEN は、**PokerStars で採用されている Mixed Game のルールを基本**として制作しています。

ただし、学習しやすさとデジタル環境での操作性を優先するため、実際のPoker Tableとは一部異なる処理があります。

主な例：

- Showdown では Hand を同時表示
- Burn Card は使用しない
- No Limit / Pot Limit では代表的な Bet Size を Preset 表示

実際の大会やPoker Roomでプレイする場合は、その会場で採用されているルールや運用を確認してください。

## Settings

以下の設定に対応しています。

- SE ON / OFF
- SE Volume
- Animation
- 4-Color Deck
- Learning Panel
- Action Hint
- Draw History

Rule Bar はゲーム識別情報として常時表示されます。

## Paid Version

有料版も将来的に開発予定です。

成績分析、Hand History、追加Game、Challenge Mode、BGMや演出強化などを検討しています。

## Usage

このリポジトリは、GitHub Pages で HEIGHTEN を公開するためにソースコードを閲覧可能な状態で配置しています。

**ソースコードを公開していることは、自由利用・再配布・改変・商用利用を許可することを意味しません。**

### All Rights Reserved / 閲覧目的公開

Copyright © HEIGHTEN. All Rights Reserved.

本リポジトリ内のコード、文章、UI、ゲーム構成、デザインその他のコンテンツについて、明示的な許可なく以下を行うことを禁止します。

- 複製
- 改変
- 再配布
- 派生物の公開
- 商用利用
- 他サービス・アプリへの転用

閲覧および GitHub Pages 上での HEIGHTEN の利用を目的として公開しています。

詳細は [`LICENSE.txt`](./LICENSE.txt) を確認してください。

## Repository Structure

```text
/
├─ index.html    # GitHub Pagesの起動ファイル
├─ .build/       # HEIGHTEN v1.4.9 本体の圧縮データ
├─ README.md     # このファイル
├─ LICENSE.txt   # 利用条件
└─ .nojekyll     # GitHub Pages用
```

`.build` は公開時の内部データです。通常の利用では編集する必要はありません。

## GitHub Pages

GitHub のリポジトリ設定から **Settings → Pages** を開き、公開元をこのリポジトリの対象Branch / root に設定すると公開できます。

`index.html` からHEIGHTEN本体を読み込みます。

---

HEIGHTEN is a browser-based Mixed Game Poker trainer.
