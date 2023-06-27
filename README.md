# AirTicketBookingServices_Backend-Development

AirTicketBookingServices is a backend development project that utilizes a microvalent architecture to provide various services for air ticket bookings. It consists of multiple microservices, each responsible for a specific aspect of the application.

## Microservices

### Booking Service
The Booking Service handles the core functionality of booking flights. It allows users to search for available flights, select seats, and make reservations. This service interacts with the FlightsAndSearchService to retrieve flight data and manages the booking process.
```
GITHUB LINK FOR AirTicketBookingService : https://github.com/ChampionVikash/AirTicketBookingService
```


### Auth Service
The Auth Service is responsible for authentication and authorization within the application. It validates incoming requests for email and password, ensuring secure access to the booking functionalities. This service plays a crucial role in user authentication and protects sensitive data.

```
GITHUB LINK FOR Auth_Service: https://github.com/ChampionVikash/Auth_Service
```

### Flights and Search Service
The Flights and Search Service provides functionalities related to flights and search operations. It offers filters to retrieve information about all cities and airports, allowing users to search for specific flight routes and destinations. It also implements the necessary CRUD operations for managing flight data.

```
GITHUB LINK FOR FlightsAndSearchService : https://github.com/ChampionVikash/FlightsAndSearchService
```

### Reminder Service
The Reminder Service handles notifications and reminders for users. It sends timely reminders for upcoming flights, updates on booking status, and other relevant information. This service ensures users stay informed throughout the booking process and helps enhance their overall experience.

```
GITHUB LINK FOR ReminderService : https://github.com/ChampionVikash/ReminderService/commits/master
```

### API Gateway
The API Gateway acts as an intermediate layer between the client-side and the microservices. It handles the incoming requests from clients and makes decisions on which microservice should respond to each request. The API Gateway performs message validation, response transformation, and rate limiting to ensure efficient and secure communication with the microservices.

```
GITHUB LINK FOR API_Gateway: https://github.com/ChampionVikash/API_Gateway
```

## Setup and Configuration
To set up and run the AirTicketBookingServices project, follow these steps:

1) Clone the repository: git clone <repository-url>
2) Install dependencies: npm install
3) Configure environment variables: Create a .env file and set the required variables for each microservice (e.g., database connection, API keys, etc.)
 4)  Start the microservices: Run npm start for each microservice individually (Booking Service, Auth Service, Flights and Search Service, and API Gateway).
 5) Access the APIs: The API Gateway will expose the endpoints for client communication.

Please refer to the individual microservices' README files for more detailed instructions on configuration and usage.

## Technologies Used

* Node.js
* Express.js
* MongoDB 
* MySQL
* Git
* Github
* Thunder Client
  
  
  
### Contributing
Contributions to the AirTicketBookingServices project are welcome! If you find any bugs or have suggestions for improvements, please submit an issue or open a pull request.

### License

Feel free to modify the above template to fit your project's specific details, add relevant sections such as API documentation, deployment instructions, and any other necessary information.
