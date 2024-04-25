בפרוקיט זה נשתמש בדרך כתיבת קוד OOP
בנאי שמקבל את הפרמטרים
public class Person {

     String name;
     String nationality;
     String dateOfBirth;
     String[] passport;
     int seatNumber;

     public Person(String name, String nationality, String dateOfBirth, int seatNumber) {
        this.name = name;
        this.nationality = nationality;
        this.dateOfBirth = dateOfBirth;
        this.seatNumber = seatNumber;
     }
     
}

קובץ ראשי שמתמש בפרמטרים בדרך כתיבת קוד OOP

 
public class Main {
  
    public static void main(String[] args) {
        Person person = new Person("jeck spero", "caribim", "32/6/1764",3 );
 
        
        System.out.println("Name: " + person.name + "\n" + "Nationality: " 
        + person.nationality + "\n" + "Date of Birth: " + person.dateOfBirth + 
        "\n" + "Seat Number: " +person.seatNumber + "\n");
        

    }
  
  
}
