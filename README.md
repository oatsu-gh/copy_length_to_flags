# copy_length_to_flags
 UTAUのノート長をフラグ欄にコピーするプラグイン

## 仕様

### 「フラグにノート長をコピーする」プラグイン

`Length=480` & `Flags=g-2H40` → `Flags=【480】g-2H40`

### 「フラグからノート長を削除する」プラグイン

`FFlags=【480】g-2H40` → `Flags=g-2H40`

## 仕様

pyファイルは共通で、plugin.txt によって呼び出すバッチファイルを切り替える。

## 開発環境

- Windows 10
- Python 3.9.5
- utaupy 1.11.3 のあとの開発版