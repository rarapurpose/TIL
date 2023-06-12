``` java
public class _01_String1 {
    public static void main(String[] args) {
        String s = "I like Java and Python and C.";
        System.out.println(s);

        // 文字列の長さ
        System.out.println(s.length()); // 29

        // 大文字と小文字の変換
        System.out.println(s.toUpperCase()); // 大文字
        System.out.println(s.toLowerCase()); // 小文字

        // 包含関係
        System.out.println(s.contains("Java")); // 含まれている場合 true
        System.out.println(s.contains("C#")); // 含まれていない場合 false
        System.out.println(s.indexOf("Java")); // 位置情報7
        System.out.println(s.indexOf("C#")); // 含まれていない場合 -1
        System.out.println(s.indexOf("and")); // 最初に一致する位置情報 (12)
        System.out.println(s.lastIndexOf("and")); // 最後に一致する位置情報 (23)
        System.out.println(s.startsWith("I like")); // この文字列で始まる true (または false)
        System.out.println(s.endsWith(".")); // この文字列で終わると true (または false)
    }
}
```

+ contains method : 文字列に特定の要素が含まれているか確認
+ indexOf method : 指定された部分文字列が最初に登場した位置を、文字列の先頭を0としたインデックス番号で返し

