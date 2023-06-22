```java

public class _09_MultipleTable {
    public static void main(String[] args) {
        // multiplication tables
        // 2 * 1 = 2
        // 2 * 2 = 4

        for (int i = 2; i < 10; i++) {
            for (int j = 1; j < 10; j++) {
                System.out.println(i + " x " + j + " = " + (i * j));
            }
            System.out.println();
        }
    }
}

```

+ 증감 연산자   
피연산자 ++  다른 연산을 수행한 후에 피연산자의 값을 1 증가시킴   
++ 피연산자  다른 연산을 수행하기 전에 피연산자의 값을 1 증가시킴
