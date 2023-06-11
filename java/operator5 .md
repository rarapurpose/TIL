```java

public class _05_Operator5 {
    public static void main(String[] args) {
        // 三項演算子
        // 結果=（条件）？ （真の場合は結果値）：（偽の場合は結果値）
        int x = 3;
        int y = 5;
        int max = (x > y) ? x : y;
        System.out.println(max); // 5

        int min = (x < y) ? x : y;
        System.out.println(min); // 3

        boolean b = (x == y) ? true : false;
        System.out.println(b); // false

        String s = (x != y) ? "different" : "same";
        System.out.println(s); // different
    }
}
```

+ 三項演算子  삼항연산자   
조건 (삼항) 연산자는 JavaScript에서 세 개의 피연산자를 받는 유일한 연산자   
앞에서부터 조건문, 물음표( ? ), 조건문이 참(truthy)일 경우 실행할 표현식, 콜론( : ),    
조건문이 거짓(falsy)일 경우 실행할 표현식이 배치


