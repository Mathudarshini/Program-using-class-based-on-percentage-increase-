
class PercentageIncrease {
double originalPrice;
double newPrice;
double percentageIncrease;

PercentageIncrease(double originalPrice, double newPrice) {
    this.originalPrice = originalPrice;
    this.newPrice = newPrice;
    calculatePercentageIncrease();
}

void calculatePercentageIncrease() {
    percentageIncrease = ((newPrice - originalPrice) / originalPrice) * 100;
}

void displayDetails() {
    System.out.println("Original Price: $" + originalPrice);
    System.out.println("New Price: $" + newPrice);
    System.out.println("Percentage Increase: " + percentageIncrease + "%");
}

}

public class Main {
public static void main(String[] args) {
PercentageIncrease priceIncrease = new PercentageIncrease(100, 120);
priceIncrease.displayDetails();
}
}

Output:

Original Price: $100.0
New Price: $120.0
Percentage Increase: 20.0%# Program-using-class-based-on-percentage-increase-
