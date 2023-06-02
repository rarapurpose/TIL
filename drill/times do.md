

```ruby
sum = 1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9 + 10
--------
sum = 0

10.times do |i|
  sum = sum + i + 1
end

puts sum

or

sum = 0

10.times do |i|
  sum += i + 1
end

puts sum
```

＋ timesを使って繰り返し処理

