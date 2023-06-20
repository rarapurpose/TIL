``` java
public class _08_NestedLoop {
    public static void main(String[] args) {
        // 二重繰り返し

        // *正方形
        /*

        *****
        *****
        *****
        *****
        *****

         */
        for (int i = 0; i < 5; i++) {
            for (int j = 0; j < 5; j++) {
                System.out.print("*");
            }
            System.out.println();
        }

        System.out.println("-----------------");

        // 星(*) 左三角形
        /*

        *
        **
        ***
        ****
        *****

         */
        for (int i = 0; i < 5; i++) {
            // for (int j = 0; j < i + 1; j++) {
            for (int j = 0; j <= i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }

        System.out.println("-----------------");

        // 星（*）右三角形
        /*

             *
            **
           ***
          ****
         *****

         SSSS*
         SSS**
         SS***
         S****
         *****

         */
        for (int i = 0; i < 5; i++) {
            for (int j = 0; j < 4 - i; j++) {
                System.out.print(" ");
            }
            for (int k = 0; k <= i ; k++) {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
