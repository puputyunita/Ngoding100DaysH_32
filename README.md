# Ngoding100DaysH_32
package ngoding100dysh_32;

import java.util.Scanner;

public class Ngoding100dysH_32 {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("masukksn inputan : ");
        String a = input.nextLine();
        if (a.length() == 1) {
            char puput = a.charAt(0);
            System.out.println(puput + " : char");
        } else {
            System.out.println("int");
        }
    }

}
