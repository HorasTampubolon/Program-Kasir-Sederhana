# Program-Kasir-Sederhana
Pada kesempatan ini, kita akan membuat Program Kasir Sederhana, dengan menggunakan bahasa pemrograman Java

public class ProgramKasir {

     public static void main(String[] args) {
    Scanner sc = new Scanner (System.in);
    int jumlahberas;
    int hargaberasperkg;
    double hargasebelumdiskon;
    double uangyangdibayarkan;
    double diskon;
    double hargasetelahdiskon;
    
        System.out.println("Toko Beras Horas");
        System.out.println("Menyediakan Beras Asli Samosir");
        System.out.println("Horas");
        System.out.println("Harga Beras per Kg = ");
        hargaberasperkg = sc.nextInt();
        System.out.println("Jumlah Beras = ");
        jumlahberas = sc.nextInt();
        hargasebelumdiskon = hargaberasperkg*jumlahberas;
        diskon = (jumlahberas*10000)*0.05;
        System.out.println("Diskon 5%");
        hargasetelahdiskon = hargasebelumdiskon - diskon;
        System.out.println("Harga Setelah Diskon = " +hargasetelahdiskon);
        System.out.println("Harga Sebelum Diskon = " +hargasebelumdiskon);
        System.out.println("Diskon = " +diskon);
        System.out.println("Harga Setelah Diskon = " +hargasetelahdiskon);
        System.out.print ("Uang yang Dibayarkan =  ");
        uangyangdibayarkan = sc.nextDouble();
        double kembalian = uangyangdibayarkan - hargasetelahdiskon;
        System.out.println("Kembalian = " +kembalian);
    // TODO code application logic here
    }
    
}
![image](https://user-images.githubusercontent.com/91046943/133965373-19de86d7-dfcb-4eea-ad54-9d86116548ee.png)
