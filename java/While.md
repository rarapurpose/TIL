```
public class _06_While {
    public static void main(String[] args) {
        // 繰り返し While
        // 例）プール

        int distance = 25; // 全距離 25m
        int move = 0; // 現在の移動距離 0m
        while (move < distance) { // 現在の移動距離が全距離より小さいという条件が真の間に繰り返し実行
            System.out.println("ずっと泳ぐ");
            System.out.println("現在の移動距離 : " + move);
            move += 3; // 3メーター移動
        }
        System.out.println("到着しました.");

        // 無限ループ

        move = 0;
        while (move < distance) { // 現在の移動距離が全距離より小さいという条件が真の間に繰り返し実行
            System.out.println("ずっと泳ぐ");
            System.out.println("現在の移動距離 : " + move);
        }
        System.out.println("到着しました.");
    }
}

```

```
while (条件式){
  // 繰り返しの中で実行される処理
  ...
}
```

# for 文とは異なる点<br>   　 　　
 + 初期化式や変化式はない<br>   　　　
 + 必要な変数は while 文の前で宣言などを行い、またブロックの中で条件式が変化するような処理を行う<br>   　
 + 繰り返し処理が終わることができず無限ループとなる 



