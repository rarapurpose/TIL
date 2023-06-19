``` java
ublic class _07_DoWhile {
    public static void main(String[] args) {
        // DoWhile
        int distance = 25; // 全距離 25m
        int move = 0; // 現在の移動距離 0m
        int height = 2; // 身長 2m
        while (move + height < distance) {
            System.out.println("続けて泳ぐ");
            System.out.println("現在の移動距離 : " + move);
            move += 3; // 3m 移動
        }
        System.out.println("到着");

        System.out.println(" --- DoWhile #1 ---");

        // もし巨人なら
        move = 0;
        height = 25; // 身長 25m
        while (move + height < distance) {
            System.out.println("続けて泳ぐ");
            System.out.println("現在の移動距離 : " + move);
            move += 3; // 3m 移動
        }
        System.out.println("到着");

        System.out.println(" --- DoWhile  #2 ---");

        // Do While  
        do {
            System.out.println("続けて泳ぐ");
            System.out.println("現在の移動距離 : " + move);
            move += 3;
        } while (move + height < distance);
        System.out.println("到着");
    }
}
```

# while文とdo-while文の違:   
条件式が初めからfalseの場合にwhile文ではブロック内の処理が1度も行われないのに対して、do-while文ではブロック内の処理が1度は行われる点。

```
do {処理} while (条件式);
```

