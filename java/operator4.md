```javascript

    public static void main(String[] args) {
        // 論理演算子
        boolean pizza = true;
        boolean tomato = true;
        boolean steak = true;

        System.out.println(pizza || tomatotomato || steak); // 一つでもtrueならばtrue    ||는 or
        System.out.println(pizza && tomato && steak); // すべてtrueの場合はtrue          && 는 and

        // And 演算
        System.out.println((5 > 3) && (3 > 1)); // 5は3より大きく、3は1より大きい(true)
        System.out.println((5 > 3) && (3 < 1)); // 5は3より大きく、3は1より小さい (false)

        // Or 演算
        System.out.println((5 > 3) || (3 > 1)); // 5は3より大きいか、3は1より大きい (true)
        System.out.println((5 > 3) || (3 < 1)); // 5は3より大きいか、3は1より小さい (true)
        System.out.println((5 < 3) || (3 < 1)); // 5は3より小さいか、3は1より小さい (false)

  
        // 論理否定演算子
        System.out.println(!true); // false
        System.out.println(!false); // true
        System.out.println(!(5 == 5)); // false
        System.out.println(!(5 == 3)); // true
    }
}

      // System.out.println(1 < 3 < 5); // 不可
```

<h2> boolean </h2>
 “true” and “false.”
