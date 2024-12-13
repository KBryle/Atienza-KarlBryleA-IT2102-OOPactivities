# *HealthSync: A Patient_Doctor Appointment Management System*

## I. Project Overview
This project, HealthSync, is a user-friendly Hospital Management System designed to simplify and improve the way healthcare facilities manage their workflows. It offers features like user authentication, patient and doctor record management, and appointment scheduling. The system is built with scalability and efficiency in mind, making it a practical solution for modern healthcare needs.

At its core, the project leverages key object-oriented programming (OOP) principles to ensure a robust and maintainable design. Encapsulation is implemented by keeping attributes private and accessing them through public methods, ensuring data security and clarity. For instance, user passwords are handled securely and validated with dedicated methods. Abstraction is achieved through a Person class, which serves as a blueprint for shared attributes like id and name, while subclasses like Patient and Doctor add specific details. Inheritance allows these subclasses to reuse properties and methods from the parent Person class, saving development time and reducing redundancy. Polymorphism comes into play with the displayInfo method, which is customized in the Patient and Doctor classes to provide unique, relevant details for each.
## II. Application of Object-Oriented Programming Principles
**Encapsulation**

Ensures that sensitive data is protected and only accessible through controlled methods. In this project, class attributes like a patient’s age or a user’s password are private, meaning they can't be directly accessed from outside the class. Instead, public methods like getAge() or validatePassword() allow secure access and validation. This design keeps data safe and ensures that only authorized interactions happen with sensitive information.

**Inheritance**

Simplifies the design by allowing classes to reuse common features. The Patient and Doctor classes inherit shared attributes and behaviors, such as id and name, from the Person superclass. This eliminates redundancy because these shared properties don’t have to be rewritten for every new type of person. At the same time, Patient and Doctor add their own specific features, like age for patients and specialization for doctors.

**Polymorphism**

Allows the program to use a common method in different ways depending on the context. The displayInfo() method is a perfect example. While it's defined in the Person superclass, both the Patient and Doctor classes override it to provide their own specific details. For instance, calling displayInfo() on a patient displays their age, gender, and contact, while calling it on a doctor shows their specialization. This flexibility makes the system adaptable and efficient.

**Abstraction**

It helps by focusing on the essential features of an object and hiding unnecessary details. The Person class is abstract, meaning you can’t create a generic "person" object—it only serves as a foundation for more specific types like Patient or Doctor. This approach ensures that each class focuses on what makes it unique while still maintaining a clear and organized overall structure.

## Sustainable Development Goal (SDG) and its Integration

* **SDG 3: Good Health and Well-Being**
The integration of SDG 3 into HealthSync focuses on making healthcare delivery more efficient, organized, and accessible. By centralizing patient and doctor records and automating appointment scheduling, the system eliminates many of the challenges associated with manual management, such as lost records or missed appointments. The straightforward interface ensures that both healthcare providers and administrators can easily use the system, improving communication and coordination. HealthSync also supports SDG 3 by helping healthcare facilities provide timely and high-quality care, fostering better health outcomes for individuals and communities alike.

* **SDG 9: Industry, Innovation, and Infrastructure**
HealthSync integrates SDG 9 by leveraging technology to modernize healthcare infrastructure. The project replaces traditional, paper-based processes with a digital system built on object-oriented principles, ensuring scalability and future readiness. Its design allows for seamless data handling and efficient resource management, creating a foundation for innovation in healthcare operations. For example, the modular structure makes it easy to expand the system with features like analytics or electronic health records. By integrating SDG 9, HealthSync not only addresses current inefficiencies but also provides a path for continuous improvement and technological advancement in the healthcare industry.
## Instruction
**Start the Main Program**

* Once the program is executed using the java HospitalManagementSystem command, it will display a welcome message:
* "Welcome to HealthSync: Your partner for wellness." This message explains the purpose of the program and introduces its functionality.

**Login or Signup**

The program will present you with three options:

* Login: If you already have an account, enter your username and password.
* Signup: If you’re a new user, create an account by providing a username and password.
* Exit: Choose this option to quit the program.
**Main Menu**

* After logging in, the program will take you to the main menu, where you can perform various tasks like adding patients, viewing patient and doctor lists, scheduling appointments, or logging out. Follow the on-screen prompts to navigate through the options.

**Interactive Features**

Each option in the main menu is designed for easy interaction. For example:

* Adding a patient requires entering their name, age, gender, and contact information.
* Scheduling an appointment requires valid patient and doctor IDs and a date.
**Exit or Logout**

* When finished, you can choose the Logout option to return to the login screen or select Exit from the main menu to close the program entirely.