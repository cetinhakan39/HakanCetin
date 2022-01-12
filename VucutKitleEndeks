import java.util.Scanner;
public class Main {

    public static void main(String[] args) {
        double kilo, boy, VKİ;
        Scanner inp = new Scanner(System.in);

        System.out.println("Lütfen Kilonuzu Kilogram Cinsinden Giriniz :");
        kilo = inp.nextDouble();

        System.out.println("Lütfen Boyunuzu Metre Cinsinden Giriniz :");
        boy = inp.nextDouble();

        VKİ = kilo / (boy * boy);
        System.out.println("Vücut Kitle Indexsiniz : " + VKİ);

        if (VKİ < 18.4) {
            System.out.println("Zayıfsınız :" + VKİ);
        }
        if (VKİ < 24.9 && VKİ >= 18.5) {
            System.out.println("Normalsiniz : " + VKİ);
        }
        if (VKİ < 29.9 && VKİ >= 25.0) {
            System.out.println("Fazla Kilolu : " + VKİ);

        }
        if (VKİ >= 30.0) {
            System.out.println("Obez : " + VKİ);
        }
    }
}
