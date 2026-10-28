## Project Title
**E-Waste Collection Management System**

## Name : ALAGAMMAL V
## Register Number : 711524BEE002

## Brief Project Description

The E-Waste Collection Management System is a web-based application designed to simplify the collection, tracking, and responsible disposal of electronic waste. With the increasing use of electronic devices such as computers, mobile phones, televisions, batteries, and household appliances, electronic waste has become a significant environmental concern. Improper disposal can lead to environmental pollution and health risks.

This project provides a digital platform where users can submit electronic waste pickup requests by entering their contact details, pickup address, e-waste category, approximate weight, and preferred collection date. The submitted requests are stored in a database and displayed on a collection management dashboard.

The dashboard allows users to view collection requests, track their progress, update request statuses, and manage records. The system supports statuses such as Pending, Scheduled, Collected, Recycled, and Rejected.

The main objective is to promote sustainable waste management, improve collection efficiency, encourage responsible recycling, and reduce improper disposal of electronic waste.

## Technologies / Tools Used

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Java 17, Spring Boot
- **Database:** H2 Database
- **API:** REST API
- **Build Tool:** Maven
- **Version Control:** Git
- **Repository Hosting:** GitHub
- **Development Environment:** Visual Studio Code / IntelliJ IDEA

## Key Features

- User-friendly and responsive interface
- Electronic waste pickup request submission
- Customer details and pickup address management
- E-waste category and approximate weight selection
- Preferred pickup date selection
- Collection request dashboard
- Request status tracking and updating
- Delete collection requests
- Database storage for collection records

## Project Structure

```text
EWasteCollectionManagement/
├── README.md
├── .gitignore
└── backend/
    ├── pom.xml
    └── src/
        └── main/
            ├── java/com/ewaste/
            │   ├── EWasteApplication.java
            │   ├── controller/
            │   ├── model/
            │   └── repository/
            └── resources/
                ├── application.properties
                └── static/
                    ├── index.html
                    ├── styles.css
                    └── app.js
```

## Installation and Execution

### Prerequisites
- Java 17 or later
- Maven 3.8 or later
- Internet connection for downloading project dependencies

### Steps to Run
1. Clone or download the project repository.
2. Open the project folder in Visual Studio Code or IntelliJ IDEA.
3. Open the terminal inside the `backend` folder.
4. Execute the following command:

```bash
mvn spring-boot:run
```

5. Once the application starts, open the following URL in your browser:

```text
http://localhost:8080
```

The frontend and backend run together through the Spring Boot application.

## API Endpoints

| HTTP Method | Endpoint | Description |
|---|---|---|
| GET | `/api/requests` | Retrieve all pickup requests |
| GET | `/api/requests/{id}` | Retrieve a specific request |
| POST | `/api/requests` | Create a new pickup request |
| PATCH | `/api/requests/{id}/status` | Update request status |
| DELETE | `/api/requests/{id}` | Delete a pickup request |

## Future Enhancements

- User and administrator authentication
- Email and SMS notifications
- Location-based pickup scheduling
- Recycling centre and collection partner integration
- Reports and analytics for waste collection
- Pickup request history and progress notifications
- Integration with authorized e-waste recycling organizations

## Expected Outcome

The project aims to provide an organized and accessible platform for managing electronic waste collection. It encourages environmentally responsible disposal, improves the visibility of collection requests, and supports sustainable recycling practices.

## Conclusion

The E-Waste Collection Management System demonstrates how web development, Java backend technologies, and database integration can be used to address environmental challenges. By digitizing pickup requests and collection tracking, the system provides a foundation for efficient e-waste management and contributes to a cleaner and more sustainable future.

