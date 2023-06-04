```ruby

def check_name(str)
  # 処理を記述
end

puts "登録したい名前を入力してください"
str = gets
check_name(str)

出力例
Amy E　 → 登録が完了しました
Amy E　→!エラー!記号は登録できません
Amy E　 → !エラー!空白は登録できません
ーーーーー

def check_name(str)
  if str.include?(".")
    puts "!エラー!記号は登録できません"
  elsif str.include?(" ")    ⇒ " "스페이스 띄우기
    puts "!エラー!空白は登録できません"
  else
    puts "登録が完了しました"
  end
end
puts "登録したい名前を入力してください"
str = gets
check_name(str)

```
