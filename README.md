# DOGma
// Dog.java - Class definition
public class Dog {
    String name;
    int age;
    String breed;

    public Dog(String name, int age, String breed) {
        this.name = name;
        this.age = age;
        this.breed = breed;
    }

    public void bark() {
        System.out.println(name + " says Woof!");
    }
}
class Main {
    public static void main(String[] args) {
        // Creating objects of the Dog class
        Dog charlie = new Dog("Charlie", 3, "Beagle");
        Dog max = new Dog("Max", 5, "Bulldog");

        // Calling method on the objects
        charlie.bark();
        max.bark();
    }
}
