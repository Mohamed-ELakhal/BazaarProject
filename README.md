# Bazaar - An eCommerce Application
Bazaar is a modern eCommerce application built using Java Spring Boot for the backend and Angular/React for the frontend.


## Features
- [x] User authentication and authorization with Okta.
- [x] Product catalog with search and filtering options.
- [x] Shopping cart functionality.
- [ ] Secure payment gateway integration.
- [x] Order management and tracking.
- [ ] User profile management.
- [ ] Admin dashboard for managing products, orders, and users.
- [x] Responsive design for seamless user experience across devices.

## Technologies Used
  - Backend
    - Java 17
    - Spring Boot 3.1.0
    - Spring Data JPA
    - Spring MVC
    - MySQL (for production)
    - OpenCSV for CSV parsing (for development)
    - H2 Database (for development)
    - Angular
    - React
    - HTML, CSS, Bootstrap, TypeScript

## Setup
### Prerequisites
- JDK 17 or higher
- Maven
- Node.js and npm
- Angular CLI (installed globally)
- MySQL database

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/your-username/bazaar.git
    cd bazaar
    ```
2. Configure MySQL database settings in application.properties under `src/main/resources`.
3. Build and run the backend using Maven:
    ```bash
    mvn spring-boot:run
    ```

4. Navigate to the [frontend] directory:
    ```bash
    cd ../bazaar-frontend
    ```
5. Install frontend dependencies:
    ```bash
    npm install
    ```
6. Run the frontend ( for angular) :
    ```bash
    ng serve
    ```
   for React :
   ```bash
    npm start
    ```
   
8. Access the application in your browser at http://localhost:4200 for angular
   or http://localhost:5173/ for react.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
