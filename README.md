# Spring Security Demo Project
This demo project is designed to showcase the use of Spring Security in a Java-based web application. It provides a basic implementation of authentication and authorization features, allowing users to log in and access restricted pages.

## Prerequisites
- Java 17 or later
- Maven 3.6.3 or later
- An IDE such as IntelliJ or Eclipse
## Getting Started

1. Clone the repository to your local machine using git clone git@github.com:phanikiranthaticharla/jwt-demo.git
2. Open the project in your preferred IDE
3. Run the Maven command mvn clean install to download the dependencies
4. Run the application using the IDE or using the Maven command `mvn spring-boot:run`
5. Access the application in your web browser at http://localhost:8080
# Features
1. Login functionality
2. TODO - Access control based on user roles
3. User authentication using in-memory store
4. TODO: Password encoding using the bcrypt algorithm
## Notes
The demo uses an in-memory user store for simplicity, but in a real-world scenario, a database or other persistent storage should be used instead.
The password encoding used in the demo (bcrypt) is a secure encoding algorithm, but for real-world scenarios, additional security measures such as password salt should be used.
The demo provides a basic implementation of authentication and authorization features, and is intended to serve as a starting point for further development and customization.
## Contributing
If you would like to contribute to the project, please create a fork of the repository and submit a pull request. We welcome contributions of all types, including bug fixes, new features, and documentation improvements.

## License
This project is licensed under the MIT License - see the LICENSE file for details.


