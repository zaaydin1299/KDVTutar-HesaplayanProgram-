# KDVTutar-HesaplayanProgram-
import java.util.Scanner;


public class Main {
    public static void main(String[] args) {
    double ucret ,kdvOran = 0.18;
    
    Scanner input = new Scanner (System.in);
    System.out.println("Tutar Giriniz : " );
    ucret = input.nextDouble();

    double kdvTutar = ucret * kdvOran;
    double kdvliTutar = ucret + kdvTutar;

    System.out.println("Kdv Oranı : " + kdvOran);
    System.out.println("Kdvli Tutarı : " + kdvliTutar);
    System.out.println("Kdv Tutarı : " + kdvTutar);
    System.out.println("Kdvsiz Tutar : " + ucret);
