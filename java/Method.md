```java

public class _01_Method {
    // Method 定義
    public static void sayHello() {
        System.out.println("Hello");
    }

    public static void main(String[] args) {
        // Method　呼ぶ
        System.out.println("呼ぶ前");
        sayHello();
        sayHello();
        sayHello();
        System.out.println("呼ぶ後");
    }
}
```

``` java
public class _02_Parameter {
     //Parameter
    public static void power(int number) { // Parameter, 
        int result = number * number;
        System.out.println(number + " 의 2 승은 " + result);
    }

    public static void powerByExp(int number, int exponent) {
        int result = 1;
        for (int i = 0; i < exponent; i++) {
            result *= number;
        }
        System.out.println(number + " 의 " + exponent + " 승은 " + result);
    }

    public static void main(String[] args) {
        // 전달값, Parameter
        // 2 -> 2 * 2 = 4
        // 3 -> 3 * 3 = 9

        // Argument, 인수
        power(2); // 2 * 2 = 4
        power(3); // 3 * 3 = 9

        powerByExp(2, 3); // 2 * 2 * 2 = 8
        powerByExp(3, 3); // 3 * 3 * 3 = 27
        powerByExp(10, 0); // 1
    }
}
```
