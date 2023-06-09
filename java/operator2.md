```java

    public static void main(String[] args) {
        // 代入演算子
        int num = 10;
        
        num = num + 2;     
        System.out.println(num); // 12    

        num = num - 2;
        System.out.println(num); // 10

        num = num * 2;
        System.out.println(num); // 20

        num = num / 2;
        System.out.println(num); // 10

        num = num % 2;
        System.out.println(num); // 0

        // 複合代入演算子
        num = 10;
        // num = num + 2;
        num += 2;
        System.out.println(num); // 12

        // num = num - 2;
        num -= 2;
        System.out.println(num); // 10

        // num = num * 2;
        num *= 2;
        System.out.println(num); // 20

        // num = num / 2;
        num /= 2;
        System.out.println(num); // 10

        // num = num % 2;
        num %= 2;
        System.out.println(num); // 0
    }

