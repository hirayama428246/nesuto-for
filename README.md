# nesuto-for
//ネストfor分
public class Main {
 public static void main(String[] args) {
        int n = 4;
        int i = 0;
        for (int j = 0; j < n; j++) {
            if (i > j) {
                System.out.print("　");
            } else {
                System.out.print("●");
            }
        }
        System.out.println();
        i = 1;
        for (int j = 0; j < n; j++) {
            if (i > j) {
                System.out.print("　");
            } else {
                System.out.print("●");
            }
        }
        System.out.println();
        i = 2;
        for (int j = 0; j < n; j++) {
            if (i > j) {
                System.out.print("　");
            } else {
                System.out.print("●");
            }
        }
        System.out.println();
        i = 3;
        for (int j = 0; j < n; j++) {
            if (i > j) {
                System.out.print("　");
            } else {
                System.out.print("●");
            }
        }
        System.out.println();
 }
}
