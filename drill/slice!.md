```ruby

def missing_char(str, n)
  # 処理を記述
end

# 呼び出し例（1つ目の引数には対象となる文字列を、2つ目の引数には対象となる
  文字列から何番目の文字を削除するのかを指定しましょう）
missing_char('kitten', 1)
----------------------------------------------

def missing_char(str, n)
  str.slice!(n - 1)
  puts str
end

# 呼び出し例
missing_char('kitten', 1)

```

+ slice : 配列、文字列、ハッシュから直感的に情報を取り出すことができる。指定した範囲の文字列を抽出する方法
+ slice! : 指定した範囲の文字列を部分的に削除することができる。レシーバ自身の指定した範囲の文字列が削除


```
slice ex)

str = "milkman !!"
 
puts str.slice(2)
 
puts str.slice(1..4)
 
puts str.slice(/\w+/)

print)
l
ilkm
milkman

```

```
slice! ex)
str = "milkman !!"
str.slice!(2)
puts str
 
str = "milkman !!"
str.slice!(1..4)
puts str
 
str = "milkman !!"
str.slice!(/\w+/)
puts str

print)
mikman !!
man !!
 !!
```

