```ruby
user_data = [
 {user: {profile: {name: 'George'}}},
 {user: {profile: {name: 'Alice'}}},
 {user: {profile: {name: 'Taro'}}},
]
```


```
出力
George
Alice
Taro
```

```
user_data.each do |u|
  puts u[:user][:profile][:name]
end

あるいは
user_data.each{ |u| puts u.dig(:user, :profile, :name) }
```

+ 取得したい値に対応するキーは、nameというキー
nameというキーまで連続して指定すると、George、Alice、Taroという値が得られる
