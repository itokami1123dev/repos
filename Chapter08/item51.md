* 項目51 文字列結合のパフォーマンスに用心する

小さな固定サイズの文字列結合には文字列結合演算子で良い。

ループを伴う等の場合はStringBuilderを使う事。

さらにシビアなパフォーマンスを求められる場合は、[「性能面でセンシティブな場面で String を使うことを考えるな。CharBuffer 使え。」](http://d.hatena.ne.jp/aoe-tk/20140409/1397059399)ってことで。

