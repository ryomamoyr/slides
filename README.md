# Marpによるスライドの作成

## 想定
* VScode + Marpでスライドを作成することを想定
* template_project/template_event/template.mdをコピペして使うことを想定
* プロジェクト毎に管理することを想定
  * 各報告会毎に管理することを想定


## プロジェクト毎のフォルダ管理について

```text
project_name/
├── yyyyMMdd_eventA/
│   ├── images/
│   └── yyyyMMdd_報告資料.md
└── yyyyMMdd_eventB/
    ├── images/
    └── yyyyMMdd_報告資料.md
```
このように各プロジェクトディレクトリの中に報告会などのイベントのディレクトリがある構造を想定しています。

各イベントのディレクトリの中にスライド(.mdファイル)とスライドに貼るための画像をまとめるディレクトリがあるように作成しています。

###  例
```text
├── A社
│   └── yyyyMMdd_中間報告会
        ├── images
        └── 報告資料.md
```


## 設定

細かい設定はtheme.cssで変更可能です。  
theme.cssには以下が定義されています
  - タイトルスライド
  - 目次スライド
  - 章区切りスライド

