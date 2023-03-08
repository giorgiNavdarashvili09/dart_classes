# dart_classes

```dart
void main() {
  
  
  User user = User(
    firstName: "giorgi",
    lastName: "navdarashvili",
    age: 27,
  );
  
  User user2 = User(
    firstName: "Nino",
    lastName: "Otarashvili",
    age: 20
  );

  var fullName = user.printFullname();
  print(fullName);

}


class User {
  User({
    required this.firstName,
    required this.lastName,
    required this.age,
  });
  
  String firstName;
  String lastName;
  int age;
  
  String printFullname() {
    return firstName + " " + lastName;
  }
 
  
  void register() {
    //...
    //..
    //...
  }

}
```
