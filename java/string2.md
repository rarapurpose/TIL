```java
public class _02_String2 {
    public static void main(String[] args) {
        String s = "I like Java and Python and C.";

        // 文字列変換
        System.out.println(s.replace(" and", ",")); // " and" ⇒"," 
        System.out.println(s.substring(7)); // index基準7から開始（以前の内容は削除）
        System.out.println(s.substring(s.indexOf("Java")));
        // "Java" が始まる位置から、"." この始まる位置の直前まで
        System.out.println(s.substring(s.indexOf("Java"), s.indexOf("."))); // 開始位置から終了位置「直前」まで

        // スペースを削除
        s = "        I love Java.      ";
        System.out.println(s);
        System.out.println(s.trim()); // 前後のスペースを削除

        // 文字列の結合
        String s1 = "Java";
        String s2 = "Python";
        System.out.println(s1 + s2); // JavaPython
        System.out.println(s1 + "," + s2); // Java,Python
        System.out.println(s1.concat(",").concat(s2)); // Java,Python
    }
}
