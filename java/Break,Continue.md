# Break
```java
public class _10_Break {
    public static void main(String[] args) {
        // Break
        // 20個だけ販売　（一人１個）
        // 50名待機

        // For 문
        int max = 20;
        for (int i = 1; i <= 50; i++) {
            System.out.println(i + "番の物が出来上がりました.");　　
            if (i == max) {
                System.out.println("完売です");
                break; // 繰り返しstop
            }
        }
        System.out.println("営業終わりました");

        System.out.println("---------------------");

        // While 
        int index = 1; // 待機番号
        while (index <= 50) {
            System.out.println(index + "番の物が出来上がりました");
            if (index == max) {
                System.out.println("完売です");
                break;
            }
            index++;
        }
        System.out.println("営業終わりました.");
    }
}
```
# Continue

```java
public class _11_Continue {
    public static void main(String[] args) {
        // Continue

        // NOSHOWした場合として
        // For
        int max = 20; //　最大販売
        int sold = 0; // 現在販売数量
        int noShow = 17; // 待機番号のなかNOSHOW
        for (int i = 1; i <= 50; i++) {
            System.out.println(i + "번 손님, 주문하신 치킨 나왔습니다.");

            // 손님이 없다면? (noShow)
            if (i == noShow) {
                System.out.println(i + "번 손님, 노쇼로 인해 다음 손님에게 기회가 넘어갑니다.");
                continue;
            }

            sold++; // 판매 처리
            if (sold == max) {
                System.out.println("금일 재료가 모두 소진되었습니다.");
                break;
            }
        }
        System.out.println("영업을 종료합니다.");

        System.out.println("------------------");
        // While 문
        sold = 0;
        int index = 0; // お客様番号
        // while (index <= 50) {
        while (true) {
            index++;
            System.out.println(index + "番の物が出来上がりました.");

            // noShow
            if (index == noShow) {
                System.out.println(index + "番の物はキャンセル致します");
                continue;
            }

            sold++; //　販売処理
            if (sold == max) {
                System.out.println("完売です");
                break;
            }
        }
        System.out.println("営業終わりました");
    }
}
