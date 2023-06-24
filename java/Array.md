```
public class _01_Array {
    public static void main(String[] args) {
        // 配列 : 同じデータ型の複数の値を格納する連続したスペース
        String coffeeRoss = "Americano";
        String coffeeRachel = "Mocha";
        String coffeeChandler = "Latte";
        String coffeeMonica = "Cappuccino";

        System.out.println(coffeeRoss + " one"); //Americano　one
        System.out.println(coffeeRachel + " one");
        System.out.println(coffeeChandler + " one");
        System.out.println(coffeeMonica + " one");
        System.out.println("ください");

        // １方法
        // String[] coffees = new String[4];

        // ２方法
        // String coffees[] = new String[4];
//        coffees[0] = "Americano"; // 0 から
//        coffees[1] = "Mocha";
//        coffees[2] = "Latte";
//        coffees[3] = "Cappuccino";

        // ３方法
        // String[] coffees = new String[] { "Americano", "Mocha", "Latte", "Cappuccino" };

        // ４方法
        String[] coffees = { "Americano", "Mocha", "Latte", "Cappuccino" };

        System.out.println("---------------------------");

        // order
        System.out.println(coffees[0] + " one"); // Americano one
        System.out.println(coffees[1] + " one"); // Mocha one
        coffees[2] = "Espresso"; //   変更
        System.out.println(coffees[2] + " one");
        System.out.println(coffees[3] + " one");
        System.out.println("ください");


    }
}
