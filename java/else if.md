``` java
public class Else {
    public static void main(String[] args) {
        //  If Else
        int hour = 10;
        if (hour < 14) { // 午後2時以前の場合
            System.out.println("カフェラテ +1");
        } else { // 
            System.out.println("アメリカーノ +1");
        }
        System.out.println("注文完了#1");

        // 午後2時以降、または朝のコーヒーを飲んだ場合?
        hour = 10;
        boolean morningCoffee = false;
        if (hour >= 14 || morningCoffee == true) { // 午後2時以降、朝のコーヒーを飲んだ場合？
            System.out.println("アメリカーノ +1");
        } else { // 
            System.out.println("カフェラテ +1");
        }
        System.out.println("注文完了 #2");
    }
}
```
