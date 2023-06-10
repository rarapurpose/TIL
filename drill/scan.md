```ruby

def count_pp(str)            //count_hiメソッドの仮引数strには対象の文字列が格納---"pp"という文字列の数だけ配列の要素を返す
  puts str.scan("pp").length 
end


count_pp('abc hi ho')         //   引数には対象となる文字列を指定

```

+ scan  :検索結果を配列として返し
