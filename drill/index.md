```ruby
出力例)
count_post("postxxcode") → 1   整数の値で返し
count_post("aaapostbbb") → 4
count_post("cozexxpost") → 7 

---------------------------

def count_post(str)     任意の文字列の中から"post"が左から何文字目に出てくるか調べて、その数を出力
  puts str.index("post", 0) + 1        検索したい文字列, 検索を開始する位置
end

```

+ index method : 文字列や配列の中に指定した文字列が含まれていた場合、その文字列の開始位置を整数の値で返します。
