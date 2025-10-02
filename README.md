class Book {
    String title;
    String author;
}

public class Main {
    public static void main(String[] args) {

        Book myBook = new Book();

        myBook.title = "Java for Beginners";
        myBook.author = "John Doe";

        System.out.println("Book Title: " + myBook.title);
        System.out.println("Book Author: " + myBook.author);
    }
}


