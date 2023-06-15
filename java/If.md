```  java
public class _01_If {
    public static void main(String[] args) {
        // If
        int hour = 15; // 

        // if文内で1つの文を実行するときは{}省略可能
        if (hour < 14)
            System.out.println("カフェラテ +1");

        // if文内で2つ以上の文を実行するときは{}省略不可
        if (hour < 14) {
            System.out.println("カフェラテ +1");
            System.out.println("ショットを追加");
        }
        System.out.println("注文完了 #1");

        // 午後2時以前、朝のコーヒーを飲んでいない場合？
        hour = 10;
        boolean morningCoffee = false; //朝のコーヒー
        // if (hour < 14 && morningCoffee == false) {
        if (hour < 14 && !morningCoffee) {
            System.out.println("カフェラテ +1");
        }
        System.out.println("注文完了 #2");

        // 午後2時以降、朝のコーヒーを飲んだ場合？
        hour = 15;
        morningCoffee = true;
        // if (hour >= 14 || morningCoffee == true) {
        if (hour >= 14 || morningCoffee) {
            System.out.println("アメリカーノ +1");
        }
        System.out.println("注文完了 #3");
    }
}
```

+ boolean : true, false
