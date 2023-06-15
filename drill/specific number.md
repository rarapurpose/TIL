```ruby

def array123(nums)
  if nums.include?(1) && nums.include?(2) && nums.include?(3)
    puts "True"
  else
    puts "False"
  end
end

# 呼び出し例
array123([1, 1, 2, 3, 1])
```

+ 配列内に1,2,3が全て入っている場合は True と出力すること　   　　
+ 配列内に1,2,3の全てが入っていない場合は False と出力すること　　　

+ include? 前回commitしたinclude?を復習　⇒　指定した値が、配列中に含まれているかを判定するメソッド 　　　
　

