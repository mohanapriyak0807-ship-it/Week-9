# Week-9

class Product {
    int id;
    String name;
    double price;

    Product(int id, String name, double price) {
        this.id = id;
        this.name = name;
        this.price = price;
    }

    void display() {
        System.out.println(id + " " + name + " Rs." + price);
    }
}

class Week9 {
    public static void main(String[] args) {
        Product p1 = new Product(1, "Running Shoes", 1999);
        Product p2 = new Product(2, "Sports Cap", 499);

        p1.display();
        p2.display();
    }
}
