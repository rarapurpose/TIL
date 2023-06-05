
```ruby

teas_price = [["Chamomile", [200, 250, 220]], ["Jasmine", [100, 120, 80]], ["Rooibos", [1200, 1500]]]
 
teas_price.each do |tea|   ⇒　配列teas_priceにeach method使用
  sum = 0　　　　　　　⇒　返り値
  tea[1].each do |price|
    sum += price      ⇒　sum = sum + price解釈
  end　　
  puts "#{tea[0]}の合計金額は#{sum}円です"
end

（出力）
Chamomileの合計金額は670円です
Jasmineの合計金額は300円です
Rooibosの合計金額は2700円です
```
+ +=
sum += price      ⇒　sum = sum + price解釈
