# Flight Management System

A comprehensive web-based solution for modern airline operations, designed to streamline flight booking, reservation management, and administrative tasks. This system provides a seamless experience for both passengers and airline staff, ensuring efficient management of flight operations and customer interactions.

## Key Features

### For Passengers
- **User Authentication**
  - Secure registration and login system
  - Password recovery functionality
  - Profile management capabilities

- **Flight Booking**
  - Advanced search functionality with multiple filters
  - Real-time seat availability visualization
  - Flexible booking options for different travel classes
  - Multiple payment gateway integration

- **Reservation Management**
  - View and manage existing bookings
  - Easy cancellation process
  - Seat upgrade options
  - Booking modification capabilities

### For Administrators
- **Dashboard**
  - Comprehensive overview of flight operations
  - Real-time booking statistics
  - Revenue analytics
  - Performance metrics

- **Flight Management**
  - Add, edit, and remove flight schedules
  - Dynamic pricing management
  - Route optimization tools
  - Aircraft assignment system

- **User Management**
  - Customer database management
  - Staff access control
  - Role-based permissions
  - Activity logging

## Technical Stack

### Frontend
- HTML5 for structure
- CSS3 with responsive design
- JavaScript (ES6+) for interactivity
- Modern UI/UX principles

### Backend
- Java Spring Boot framework
- RESTful API architecture
- Secure authentication system
- Robust error handling

### Database
- MySQL relational database
- Optimized query performance
- Data integrity constraints
- Regular backup system

## Getting Started

### Prerequisites
- Java Development Kit (JDK) 11 or higher
- MySQL Server 8.0 or higher
- Maven 3.6 or higher
- Modern web browser

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yashyogeshkathane/flight-management-system
   cd Flight-Management-System
   ```

2. **Database Configuration**
   - Create a new MySQL database
   - Import the provided schema
   - Update database credentials in `application.properties`

3. **Backend Setup**
   ```bash
   cd backend
   mvn clean install
   mvn spring-boot:run
   ```

4. **Frontend Setup**
   - Open the project in your preferred code editor
   - Ensure all dependencies are installed
   - Start the development server

## Accessing the Application

- **Development Environment**: `http://localhost:8080`
- **Production Environment**: Configure your domain settings

## Security Features

- SSL/TLS encryption
- CSRF protection
- SQL injection prevention
- XSS protection
- Regular security audits

## Contributing

We welcome contributions to improve this system. Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## Support

For technical support or inquiries, please contact:
- Email: [Your Support Email]
- Issue Tracker: [GitHub Issues]

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Spring Boot Team
- MySQL Community
- All contributors and maintainers

## Features
- User Registration and Login: Passengers can create accounts and log in to access the reservation system.
- Flight Search: Users can search for available flights based on their preferred destinations and travel dates.
- Seat Availability: The system displays seat availability for each flight, allowing users to choose their seats during booking.
- Booking and Reservation: Passengers can book flights and manage their reservations.
- Admin Dashboard: Airline administrators have access to a dashboard to manage flights, seat availability, and user bookings.
- Flight Management: Admins can add, update, or remove flights from the system.
- Reservation Management: Airline staff can manage passenger reservations, including cancellations and modifications.

## Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: Java Spring Boot
- Database: MySql

### Clone the Repository
```bash
git clone https://github.com/yashyogeshkathane/flight-management-system
cd Flight-Management-System
```
### Database Setup
Create a MySQL database and import the provided schema to set up the necessary tables.

### Backend Setup
- Navigate to the backend directory
- Configure the database connection in the application.properties file.

## Access the Application
Open your web browser and visit ```http://localhost:8080``` to access the Airline Reservation Management System.


