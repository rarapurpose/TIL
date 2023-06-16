```java

public class _04_SwitchCase {
    public static void main(String[] args) {
        // Switch Case

        // 奨学金の支給
        // 1等：全額奨学金
        // 2等：半額奨学金
        // 3等：半額奨学金
        // その他：奨学金対象ではありません

        // If Else  (複数の条件または範囲に該当する条件）)
        int ranking = 4; // 等数
        if (ranking == 1) {
            System.out.println("全額奨学金");
        } else if (ranking == 2 || ranking == 3) {
            System.out.println("半額奨学金");
        } else {
            System.out.println("奨学金対象ではない");
        }
        System.out.println("照会完了 #1");

        // Switch Case  (明確なケースがある場合)
        ranking = 2;
        switch (ranking) {
            case 1:
                System.out.println("全額奨学金");
                break;
            case 2:
                System.out.println("半額奨学金");
                break;
            case 3:
                System.out.println("半額奨学金");
                break;
            default:
                System.out.println("奨学金対象ではない");
        }
        System.out.println("照会完了 #2");

        // case 2と3を統合
        ranking = 3;
        switch (ranking) {
            case 1:
                System.out.println("全額奨学金");
                break;
            case 2:
            case 3:
                System.out.println("半額奨学金");
                break;
            default:
                System.out.println("奨学金対象ではない");
        }
        System.out.println("照会完了  #3");

        // ランクに応じた価格を策定（1級：最上、4級：最下）
        int grade = 1; // ランク
        int price = 7000; // 価格
        switch (grade) {
            case 1:
                price += 1000; // price = price + 1000;
            case 2:
                price += 1000;
            case 3:
                price += 1000;
                break;
        }
        System.out.println(grade + "ランクの価格: " + price + "円");
        //1ランク : 10000円
        //2ランク : 9000円
    }
}
```

+ switch-case文はif文のように条件分岐を行うためのもの　　　   
+ if文の条件式は”true”か”false”のどちらかにならなければいけませんが、switch-case文の場合は式に値が入る   

