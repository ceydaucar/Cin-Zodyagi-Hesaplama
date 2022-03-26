# Cin-Zodyagi-Hesaplama
 Patika.dev > Java101 > Koşullu İfadeler ve Kod Blokları > Ödev2 - Çin Zodyağı Hesaplama
 
 ## Java ile kullanıcıdan doğum tarihini alıp Çin Zodyağı değerini hesaplayan program yazınız.

### Çin Zodyağı nedir?

4000 bin yıldır kullanılan bir astroloji çeşididir Çin astrolojisi ve insanları 12 değişik burç ve sembollerle tanımlar. Çin Zodyağı bu 12 burcun eşit aralıklarla(10 derece genişliğinde) sıralandığı bir hayvan halkasıdır ve yıldızlarla pek bir ilgisi yoktur.

### Çin Zodyağı nasıl hesaplanır?

Çin zodyağı hesaplanırken kişinin doğum yılının 12 ile bölümünde kalana göre bulunur.

- Doğum Tarihi %12 = 0 ➜ Maymun

- Doğum Tarihi %12 = 1 ➜ Horoz

- Doğum Tarihi %12 = 2 ➜ Köpek

- Doğum Tarihi %12 = 3 ➜ Domuz

- Doğum Tarihi %12 = 4 ➜ Fare

- Doğum Tarihi %12 = 5 ➜ Öküz

- Doğum Tarihi %12 = 6 ➜ Kaplan

- Doğum Tarihi %12 = 7 ➜ Tavşan

- Doğum Tarihi %12 = 8 ➜ Ejderha

- Doğum Tarihi %12 = 9 ➜ Yılan

- Doğum Tarihi %12 = 10 ➜ At

- Doğum Tarihi %12 = 11 ➜ Koyun


      import java.util.*;

      public class chinese_zodiac {

        public static void main(String[] args) {

          Scanner sc= new Scanner(System.in);

          System.out.println("Enter your birth year: ");
          int year = sc.nextInt();

          System.out.print("Your Chinese Zodiac Sign: ");
          
          switch(year % 12) {
          case 0:
            System.out.println("Monkey ");
            break;
          case 1:
            System.out.println("Rooster ");
            break;
          case 2:
            System.out.println("Dog ");
            break;
          case 3:
            System.out.println("Pig ");
            break;
          case 4:
            System.out.println("Mouse ");
            break;
          case 5:
            System.out.println("Bull ");
            break;
          case 6:
            System.out.println("Tiger ");
            break;
          case 7:
            System.out.println("Rabbit ");
            break;
          case 8:
            System.out.println("Dragon ");
            break;
          case 9:
            System.out.println("Snake ");
            break;
          case 10:
            System.out.println("Horse ");
            break;
          case 11:
            System.out.println("Ship ");
            break;
          }

        }

      }
