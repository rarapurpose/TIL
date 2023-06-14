```
public class _03_StringCompare {
    public static void main(String[] args) {
        // 文字列比較
        String s1 = "Java";
        String s2 = "Python";

        System.out.println(s1.equals("Java")); //文字列の内容が等しい場合はtrue、異なる場合はfalse

        // 大文字と小文字を区別せずに文字列の内容が同じかどうかを確認する
        System.out.println(s2.equalsIgnoreCase("python"));

        // + 文字列比較
        s1 = "1234"; // 
        s2 = "1234";
        System.out.println(s1.equals(s2)); // true 
        System.out.println(s1 == s2); // true 

        s1 = new String("1234");
        s2 = new String("1234");
        System.out.println(s1.equals(s2)); // true
        System.out.println(s1 == s2); // false
    }
}

