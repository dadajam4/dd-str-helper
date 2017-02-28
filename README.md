# dd-str-helper
Simple String Helper

It is a thing created to be used very privately.

## Installation

```
$ npm install dd-str-helper
```

## How to use
```
const DDStrHelper = require('dd-str-helper');

let cameled = DDStrHelper.camelCase('string');
```

## Api

### camelCase
キャメルケースへ変換 sampleString

* **param** (`string`) - string.
* **return** (`string `) - result.

### snakeCase
スネークケースへ変換 sample_string

* **param** (`string`) - string.
* **return** (`string `) - result.

### hyphenCase
ハイフンケースへ変換 sample-string

* **param** (`string`) - string.
* **return** (`string `) - result.

### pascalCase
パスカルケースへ変換 SampleString

* **param** (`string`) - string.
* **return** (`string `) - result.

### firstUpper
1文字目を大文字に変換 Upper

* **param** (`string`) - string.
* **return** (`string `) - result.

### trimBar
先頭、末尾のハイフン or アンダーバーをトリムする

* **param** (`string`) - string.
* **return** (`string `) - result.

### hash2sassmap
ハッシュをsass用の文字列に変換する

* **param** (`string`, `object`) - name, hash.
* **return** (`string `) - for sass hash.
