# kanata-config 

キーボードリマップソフト Kanata（[jtroo/kanata: Improve keyboard comfort and usability with advanced customization](https://github.com/jtroo/kanata)） の設定ファイル。

## 機能

- アルファベット下段キー（`x`、`c`、`v`、`m`、`,`、`.`）の長押しで修飾キー`Alt`、`Ctrl`、`Shift` （Bottom row mods）
- Capslock をEsc/Ctrlに置き換え（タップ→ `Esc`、 長押し → `Ctrl`）

## 使い方

### kanata のインストール方法

``` powershell
winget install jtroo.kanata_gui
```

インストール先は `$env:LOCALAPPDATA\Microsoft\WinGet\Packages\` 。

### 設定ファイルの配置

[kanata.kbd](./kanata.kbd) を
`$env:APPDATA\kanata\kanata.kbd` （Kanataのデフォルト読み込み先）に配置する。

### 実行

スタートアップフォルダ（shell:startup）に kanata-gui.exe へのショートカットを作る。


## 使用環境

- 日本語106キーボード
- Windows 11
- Kanata v1.9.0 で動作確認済み。
