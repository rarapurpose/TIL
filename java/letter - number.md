```java

   - 整数+実数演算
        score = 93 + (int) 98.8; // 93 + 98
        System.out.println(score); // 191

        score_d = (double) 93 + 98.8; // 93.0 + 98.8
        System.out.println(score_d); // 191.8

   - 変数に変換されたデータを取り込む
        double convertedScoreDouble = score; // 191 -> 191.0
        // int -> long -> float -> double (自動形変換)

        int convertedScoreInt = (int) score_d; // 191.8 -> 191
        // double -> float -> long -> int (手動形変換)

   - 数字を文字列として
        String s1 = String.valueOf(99);
        s1 = Integer.toString(99);
        System.out.println(s1); // 99

        String s2 = String.valueOf(88.8);
        s2 = Double.toString(88.8);
        System.out.println(s2); // 88.8

   - 文字列を数字へ
        int i = Integer.parseInt("33");
        System.out.println(i); // 33
        double d = Double.parseDouble("22.8");
        System.out.println(d); // 22.8

        int error = Integer.parseInt("java");
    }
}
