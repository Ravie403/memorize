# ソースファイルの基本

## ファイル名
ファイル名は必ず英小文字とアンダースコア(_)、ダッシュ(-)で構成し、句読点を入れてはいけません。ファイル名の命名そのものはあなたのプロジェクトの慣例に従いましょう。ファイル名の拡張子は`.js`でなければなりません。

## ファイルの文字エンコード
ソースファイルの文字エンコードは**UTF-8**です。

## 特殊文字
### 空白文字
行末記号シーケンスを除き、ASCIIの水平スペース文字(0x20)はソースファイルのあらゆる場所に表れる唯一の空白文字です。すなわち、

1. 文字列内の他の空白文字はエスケープされます。
2. タブ文字はインデントとして扱いません。

### 特殊なエスケープ文字

### 非ASCII文字
ASCII文字ではない文字に関しては、実際のUnicode文字(例えば`∞`)または同等の16進数、またはUnicodeエスケープ(例えば`\u221e`)のいずれかが使用されます。しかし、どれを採用するかはその文字がコードを**読みやすく、理解しやすくするか**によって決まります。