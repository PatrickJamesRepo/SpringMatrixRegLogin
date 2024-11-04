![Login Image](https://raw.githubusercontent.com/Fall2024-NSCC-ECampus/assignment-2-responsive-user-registration-w0140158/main/login.png)
![Login Image 1](https://raw.githubusercontent.com/Fall2024-NSCC-ECampus/assignment-2-responsive-user-registration-w0140158/main/login2.png)


# Responsive User Registration

This project is a responsive user registration and login system built with Spring Boot and Thymeleaf. It enables users to register, login, and logout while offering client and server-side checks for unique usernames and emails.

## Table of Contents
1. [Technologies Used](#technologies-used)
2. [Setup and Installation](#setup-and-installation)
3. [Endpoints](#endpoints)

---

## Technologies Used

- **Java**: The primary language for the backend logic.
- **Spring Boot**: For building a stand-alone, production-grade Spring-based application.
- **Spring Security**: For securing user authentication and authorization.
- **Thymeleaf**: For server-side rendering of HTML templates.
- **Bootstrap 5**: For responsive and modern UI styling.
- **H2 Database**: In-memory database used for development and testing.
- **JPA/Hibernate**: For ORM and database interactions.
- **JavaScript**: For front-end interactivity, including Matrix effect background.

---

## Setup and Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Fall2024-NSCC-ECampus/assignment-2-responsive-user-registration-w0140158.git
   cd assignment-2-responsive-user-registration-w0140158
   ```

2. **Build and Run**
    - You can build and run the application with Maven or your IDE:
      ```bash
      mvn spring-boot:run
      ```
    - Or run the application directly from your IDE.

3. **Access the Application**
    - Once running, access the application at `http://localhost:8080/register`.

---

## Endpoints

| HTTP Method | Endpoint             | Description                                |
|-------------|-----------------------|--------------------------------------------|
| GET         | `/register`           | Displays the registration form             |
| POST        | `/api/auth/register`  | Registers a new user                       |
| POST        | `/api/auth/login`     | Authenticates a user                       |
| GET         | `/index`              | Displays the index (main) page             |
| GET         | `/login`              | Displays the login form                    |
| POST        | `/api/auth/logout`    | Logs out the current user                  |
| GET         | `/api/auth/check-username` | Checks if a username already exists  |
| GET         | `/api/auth/check-email`    | Checks if an email is already registered |

---

## Additional Information

### Registration and Login
- **Register**: Users can register with unique usernames and emails.
- **Login**: Authenticates users using Spring Security, with username and password.

### Styling and UX
- Responsive design using Bootstrap 5 for both desktop and mobile views.
- Matrix background effect created with JavaScript for aesthetic.

---

## License

This project is for educational purposes.
