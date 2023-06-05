```java

public class _05_VariableNaming {
    public static void main(String[] args) {
  

     ＋例）入局申告書
        String nationality = "韓国"; 
        String firstName = "HYUNYOUNG"; 
        String lastName = "LEE"; 
        String dateOfBirth = "2033-12-31"; 
        String residentialAddress = "NARA"; 
        String purposeOfVisit = "観光"; 
        String flightNo = "KG555"; 
        String _flightNo = "KG555"; 　　　　⇒　アンダーバー
        String flight_no_2 = "KG555"; 　　　⇒　アンダーバー＋数字
        // String -flightNo = "KG555";

        int accompany = 2; 
        int lengthOfStay = 5; 
     
        final String CODE = "KR";　　　⇒　絶対に変わらない定数は大文字
    }
}
```

 ■ 変数   
 　-　(_),(abc),(123) OK（空白NG）   
 　- _ under bar,文字で始まる   
 　- 一つの単語に２個以上単語   
 　- 小文字、始まる文字は大文字   
 　- 予約語を使用不可(public, static, void, int, double, float, ...)   


