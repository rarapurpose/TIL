``` ruby

class Fruit

 def fresh       class method
   puts "This is fruit"
 end

 def initialize(name, price)      インスタンスmethod
   @name(インスタンス変数) = name 
   @price(インスタンス変数) = price
 end

 def infomation　　　　　　　　　 インスタンスmethod
   puts "#{@name}は#{@price}円です"
 end
end

banana(インスタンス) = Fruit.new("banana", 120)
melon(インスタンス) = Fruit.new("melon", 200)
grape(インスタンス) = Fruit.new("grape", 60)

Fruit.fresh
banana.infomation
melon.infomation
grape.infomation
```

+ initialize : 引数で名前と値段を渡し、インスタンス変数name,priceに代入

