# 1. Looping
1. perulangan for yang menjelaskan menggunakan int dan variabel i adalah 1. Jika i kurang dari 100. maka variabel i ditambah.
  for (int i = 1; i <= 100; i++)

2. Jika variabel i kurang dari 9 maka akan memunculkan output angka yaitu 1, 2, 3, 4, 5, 6, 7, 8, 9.
   if (i <= 9) {
  System.out.println(i);
}
3. Jika lebih dari 9 maka akan muncul output Mohammad Dimas Al Shiddiq sampai ke 100
   else {
   System.out.println("Mohammad Dimas Al Shiddiq");
}

# 2. While
1. perulangan while yang menjelaskan menggunakan int dan n adalah 2. 
   int n = 2;

2. ketika variabel n kurang dari 9 maka akan memunculkan "aku sayang kamu" sebanyak 8.
   while( n < 10 ) {
   System.out.println("Aku Sayang Kamu");

3. Jika kita menempatkan saat bertemu variabel n = 5 maka akan muncul "Aku Benci Kamu" pada variabel ke-5.
   if ( n == 5 ){
   System.out.println("Aku Benci Kamu");}

4. Jika Tidak variabel n = 5 maka akan memunculkan "Tolong Kembali" setiap variabel kelipatan ke-2 kecuali variabel ke-5.
    else {
            System.out.println("Tolong Kembali");
    }
   n++;
    }

# 3. Zodiac 
1. Pertama import scanner dan untuk dapat memasukkan tanggal lahir kita menggunakan input dengan format 29 04.
   import java.util.Scanner;

public class Zodiac {
    public static void main (String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Masukkan tanggal lahir Kamnyuu (Contoh 29 04): ");
        String tanggalLahir = input.nextLine();

        String[] parts = tanggalLahir.split(" ");
        int tanggal = Integer.parseInt(parts[0]);
        int bulan = Integer.parseInt(parts[1]);

        String zodiak = hitungZodiak(tanggal, bulan);
        System.out.println("Zodiak Anda adalah: " + zodiak);
    }
    
  2. Kemudian kita dapat menggunakan if else untuk menentukan tanggal lahir yang telah input diawal tersebut berada di zodiac apa.
     public static String hitungZodiak(int tanggal, int bulan) {
        if ((bulan == 3 && tanggal >= 21) || (bulan == 4 && tanggal <= 19)) {
            return "Aries";
        } else if ((bulan == 4 && tanggal >= 20) || (bulan == 5 && tanggal <= 20)) {
            return "Taurus";
        } else if ((bulan == 5 && tanggal >= 21) || (bulan == 6 && tanggal <= 20)) {
            return "Gemini";
        } else if ((bulan == 6 && tanggal >= 21) || (bulan == 7 && tanggal <= 22)) {
            return "Cancer";
        } else if ((bulan == 7 && tanggal >= 23) || (bulan == 8 && tanggal <= 22)) {
            return "Leo";
        } else if ((bulan == 8 && tanggal >= 23) || (bulan == 9 && tanggal <= 22)) {
            return "Virgo";
        } else if ((bulan == 9 && tanggal >= 23) || (bulan == 10 && tanggal <= 22)) {
            return "Libra";
        } else if ((bulan == 10 && tanggal >= 23) || (bulan == 11 && tanggal <= 21)) {
            return "Scorpio";
        } else if ((bulan == 11 && tanggal >= 22) || (bulan == 12 && tanggal <= 21)) {
            return "Sagittarius";
        } else if ((bulan == 12 && tanggal >= 22) || (bulan == 1 && tanggal <= 19)) {
            return "Capricorn";
        } else if ((bulan == 1 && tanggal >= 20) || (bulan == 2 && tanggal <= 18)) {
            return "Aquarius";
        } else {
            return "Pisces";
# 4. Array
1. Kode ini membuat sebuah array nama yang berisi kata-kata. Selanjutnya, menggunakan sebuah loop for, program mencetak kata-kata yang terdapat dalam array tersebut 
   satu per satu ke layar.
   
   String[] AkuSiapa = {"Kembali", "Tolong", "Please", "Comeback", "I Miss You"};
   for(int n=0; n<=4; n++){
   System.out.println("Untuk Cinta Ku " + n + " : " + AkuSiapa[n]);}
        
     
  

