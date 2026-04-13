# Goitseone-Maakwana-ST10524037-Chat-App
Chat app
import java.util.Scanner;

public class ICE_Task1 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        String customerName;
        String productName;
        double price;
        int quantity;
        double total;
        double vat;
        double finalAmount;

        System.out.print("Enter customer name: ");
        customerName = sc.nextLine();

        System.out.print("Enter product name: ");
        productName = sc.nextLine();

        System.out.print("Enter price: ");
        price = sc.nextDouble();

        System.out.print("Enter quantity: ");
        quantity = sc.nextInt();

        total = price * quantity;
        vat = total * 0.15;
        finalAmount = total + vat;

        System.out.println("Customer name: " + customerName);
        System.out.println("Product name: " + productName);
        System.out.println("Price: " + price);
        System.out.println("Quantity: " + quantity);
        System.out.println("Total before VAT: " + total);
        System.out.println("VAT: " + vat);
        System.out.println("Final amount: " + finalAmount);
        
        sc.close();
    }
}
