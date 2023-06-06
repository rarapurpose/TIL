```ruby

answer

def in1to10(num, outside_mode)　　　　　　　　　⇒　numが1以上かつ10以下の範囲であればTrueを出力
  if (num >= 1 && num <= 10) || outside_mode   ⇒　outside_modeがTrueの場合は、第一引数numが条件範囲
    puts "True"
  else
    puts "False"
  end
end

in1to10(5,false)
in1to10(11,false)
in1to10(11,true)

```
　⇒　a ||= xxx　「||」演算子の自己代入演算子。a が 偽 か 未定義 なら a に xxx を代入する
