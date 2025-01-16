# Customer Relationship Management (CRM) and Self-Care Project

## Overview
The Customer Relationship Management (CRM) and Self-Care project is a comprehensive solution designed to manage customer interactions and enhance self-service capabilities. The system streamlines customer care processes, enabling efficient handling of queries, complaints, and service requests while improving overall customer satisfaction.

## Features
- **Customer Query Management**: Handle and track customer queries and issues efficiently.
- **Self-Care Portal**: Allow customers to raise tickets, check ticket statuses, and manage their profiles.
- **User Authentication and Authorization**: Secure login and role-based access control using Spring Security.
- **Scalable Backend**: Built using Spring Boot for high performance and scalability.
- **Integration with External APIs**: Seamless integration with third-party tools and services.
- **Reporting and Analytics**: Generate reports and gain insights into customer interaction trends.

## Technology Stack
### Backend
- Java 11+
- Spring Boot (Core, Data JPA, Web, Security)
- Hibernate (ORM)
- Oracle (Database)
- Maven (Build Tool)

### Frontend (Optional: For Self-Care Portal)
- Thymeleaf
- Bootstrap / Material-UI (Styling)

### Others
- REST APIs for communication
- Postman for API testing
- Git for version control

## Installation and Setup
### Prerequisites
- Java Development Kit (JDK) 11 or above
- Maven
- MySQL Server
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/debashis-dev/CRMSC.git
   ```
2. Navigate to the project directory:
   ```bash
   cd crm-selfcare
   ```
3. Set up the database:
   - Create a MySQL database.
   - Update the `application.properties` file with database credentials:
     ```properties
     spring.datasource.url=jdbc:oracle:thin:@localhost:1521:xe
     spring.datasource.username=yourusername
     spring.datasource.password=yourpassword
     ```
4. Build the project:
   ```bash
   mvn clean install
   ```
5. Run the application:
   ```bash
   mvn spring-boot:run
   ```

## API Endpoints
### Authentication
- `POST /api/auth/login`: User login
- `POST /api/auth/register`: User registration

### Customer Management
- `GET /api/customers`: Fetch all customers
- `POST /api/customers`: Add a new customer
- `PUT /api/customers/{id}`: Update customer details
- `DELETE /api/customers/{id}`: Delete a customer

### Ticket Management
- `GET /api/tickets`: Fetch all tickets
- `POST /api/tickets`: Raise a new ticket
- `PUT /api/tickets/{id}`: Update ticket status
- `DELETE /api/tickets/{id}`: Delete a ticket


## Contact
For any queries or suggestions, feel free to contact:
- **Name**: Debashis Mohapatra
- **Email**: techie.debashis@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/debashis-developer
- 
