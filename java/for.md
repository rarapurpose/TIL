```
public class _05_For {
    public static void main(String[] args) {
        // 繰り返し For
        System.out.println("いらっしゃい ララです");
        // 別のゲストが入ってくると？
        System.out.println("いらっしゃい ララです");
        System.out.println("いらっしゃい ララです");
        System.out.println("いらっしゃい ララです");

        // 挨拶法が変わったら？
        System.out.println("こんにちは　ララです");
        System.out.println("こんにちは　ララです");
        System.out.println("こんにちは　ララです");
        // 店舗名が変わったら？
        // ララ -> ミミ
        System.out.println("こんにちは ミミです");
        System.out.println("こんにちは ミミです");
        System.out.println("こんにちは ミミです");

        System.out.println(" ---- for 文 ---- ");

        // for 文
        for (int i = 0; i < 10; i++) {
            // System.out.println("いらっしゃい ララです " + i);
            // System.out.println("こんにちは ミミです " + i);
            System.out.println("こんにちは ミミです " + i);
        }

        // 偶数のみ出力
        // 0, 2, 4, 6, 8
        for (int i = 0; i < 10; i += 2) {
            System.out.print(i);
        }

        System.out.println();

        // 奇数のみ出力
        // 1, 3, 5, 7, 9
        for (int i = 1; i < 10; i += 2) {
            System.out.print(i);
        }

        System.out.println();

        // 後ろからカウント
        // 5, 4, 3, 2, 1
        for (int i = 5; i > 0; i--) {
            System.out.print(i);
        }

        System.out.println();

        // 1から10までの数の合計
        // 1 + 2 + ... + 10 = 55
        int sum = 0;
        for (int i = 1; i <= 10; i++) {
            sum += i;
            System.out.println("現在までの総合 " + sum + "です.");
        }
        System.out.println("1 から 10 までのすべての数の合計は" + sum + "です.");
    }
}
```

```
for (初期化式; 条件式; 変化式) {
    // 条件式がtrueのときに繰り返す処理
}   

+ for文:同じ処理を繰り返し行うので、Listや配列ですべての要素に対して順番に処理を行うとき

