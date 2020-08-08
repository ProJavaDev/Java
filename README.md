public class helloWorld {
    public static void main(String[] args) {

       owter: for (int i = 1; i <= 9; i++) {
            for (int j = 1; j <= 9; j++) {

                if (i >= 5 || j >= 5) {
                   if (i<5)System.out.println();
                    continue owter;

                }
                    System.out.print(i * j == 1 ? " \t" : i * j + "\t");

            }
        }
    }
}
