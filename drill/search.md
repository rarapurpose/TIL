
```ruby
def search(target_num, input)

  input.each_with_index  do |num,index|  配列の定義 
   if num == target_num   호출된 search 메소드는 실제 인수로 설정된 값을 임시 인수 target_num 및 input으로 받음
     puts "#{index + 1}番目にあります"　　#{index + 1}` 은 배열이 0번째부터 시작하는 것을 고려
     return
    end
  end 
  puts "その数は含まれません"　　인수로 건네준 「11」은 배열 input 에는 포함되어 있지 않기 때문에, 조건에는 적용x. 따라서 "그 수는 포함되어 있지 않습니다"라고 출력
end

input = [3, 5, 9 ,12, 15, 21, 29, 35, 42, 51, 62, 78, 81, 87, 92, 93]
search(11, input)
```
