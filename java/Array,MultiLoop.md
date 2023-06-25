```java
public class _02_ArrayLoop {
    public static void main(String[] args) {
        // 配列の巡回
        String[] coffees = { "Americano", "Caffe Mocha", "Latte", "Cappuccino" };

        // for 繰り返し
        for (int i = 0; i < 4; i++) {
            System.out.println(coffees[i] + " one");
        }
        System.out.println("ください");

        System.out.println("--------------------------");

        // 長さを使用
        for (int i = 0; i < coffees.length; i++) {
            System.out.println(coffees[i] + " one");
        }
        System.out.println("ください");

        System.out.println("--------------------------");

        // enhanced for (for-each) 
        for (String coffee : coffees) {
            System.out.println(coffee + " one");
        }
        System.out.println("ください");
    }
}
```
```java
public class _03_MultiArray {
    public static void main(String[] args) {
        // 2次配列
        // 画館の座席
        // A1 - A5
        // B1 - B5
        // C1 - C5

        String[] seatA = {"A1", "A2", "A3", "A4", "A5"};
        String[] seatB = {"B1", "B2", "B3", "B4", "B5"};
        String[] seatC = {"C1", "C2", "C3", "C4", "C5"};

        // 3 x 5 2次配列
        String[][] seats = new String[][] {
                {"A1", "A2", "A3", "A4", "A5"},
                {"B1", "B2", "B3", "B4", "B5"},
                {"C1", "C2", "C3", "C4", "C5"}
        };

        // B2 にアクセスするには？
        System.out.println(seats[1][1]);

        // C5 にアクセスするには？
        System.out.println(seats[2][4]);

        
        String[][] seats2 = {
                {"A1", "A2", "A3"},
                {"B1", "B2", "B3", "B4"},
                {"C1", "C2", "C3", "C4", "C5"}
        };

        // A3 にアクセスするには？
        System.out.println(seats2[0][2]);

        // A5 にアクセスするには？
        // System.out.println(seats2[0][4]);

        // 3次元配列を作成する（縦×横×高さ）
        String[][][] marray = new String[3][3][3];
    }
}

