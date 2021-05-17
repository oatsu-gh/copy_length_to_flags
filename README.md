# copy_length_to_flags

フラグにノート長をコピーする／削除するUTAUプラグイン

## インストール

copy_length_to_flags.zip をダウンロードして、D&Dでインストールしてください。

## 仕様

以下の機能を自動で切り替えます。
- 全ノートのフラグにノート長が記入されている場合は、フラグからノート長を削除する。
    - `Length=480` & `Flags=g-2H40` → `Flags=【480】g-2H40`
- フラグにノート長が記入されていないノートが一つでもある場合は、ノート長を記入する。
    - `Flags=【480】g-2H40` → `Flags=g-2H40`

## 開発環境

- Windows 10
- Python 3.9.5
- utaupy 1.11.3 のあとの開発版

## 更新履歴

### v0.0.1（2021-05-16）

- 「フラグにノート長をコピーするプラグイン」と「フラグからノート長を削除するプラグイン」を別々に配布

### v1.0.0（2021-05-17）

- 「フラグにノート長をコピーする／削除するプラグイン」に統合して配布