# Cyber-Physical Social Systems (CPSS) - Privacy Preserved Profile Publishing

This repository contains the implementation of a **Cyber-Physical Social System (CPSS)** aimed at providing **privacy-preserved profile publishing**. CPSS is an advanced concept combining elements of cyber-physical systems with social networking platforms. This project focuses on addressing the privacy concerns users face when sharing physical and location data in a CPSS while maintaining social utility, using a novel framework to protect users' sensitive data and allow them to build their social profiles.

## Technologies and Tools Used

### 1. Java
Java was used as the core programming language to build the system. The platform-independent nature of Java allows the application to run across various operating systems. The application also utilizes:
- **JSP (JavaServer Pages)**: For dynamic web page creation and server-side logic.
- **Servlets**: To handle HTTP requests and responses.
- **JDBC (Java Database Connectivity)**: To interact with the MySQL database for storing user data.

### 2. MySQL
The application uses **MySQL** as the backend database to store user profiles, location data, and other relevant information. It ensures data consistency, security, and high performance when handling large datasets.

### 3. Tomcat Server
The **Apache Tomcat Server** was used to deploy and test the application. It is responsible for serving the web pages created using JSP and handling server-side requests.

### 4. HTML/CSS/JavaScript
The front-end of the system is developed using **HTML**, **CSS**, and **JavaScript** for a responsive and user-friendly interface. JavaScript is also used for input validation and enhancing user interactions.

## Features of the Project

- **Privacy Preservation Mechanism**: Users' physical profiles (such as mobility patterns) are carefully handled to prevent adversaries from tracking sensitive personal data.
- **Social Utility Maintenance**: The system ensures that users can still build social profiles, attract followers, and participate in social interactions while their privacy is protected.
- **Record Publishing Algorithm**: The system uses a heuristic algorithm to maximize the number of records published while adhering to privacy constraints.
- **Interactive Features**: Users can register, upload photos, write comments, and track locations while maintaining privacy.

## Modules

### 1. Admin Module
- Admins can view and authorize users, view user locations, and track sensitive user data with multiple markers on Google Maps.

### 2. User Module
- Users can register, login, and view their profiles. They can also track friends, view visited locations, and share photos with comments and ratings.

## Development Process

The development process follows a structured software development lifecycle, which includes:
- **Problem Identification**: Analyzed privacy concerns in CPSS and proposed a solution.
- **System Design**: Created UML diagrams (use case, sequence, and class diagrams) and data flow diagrams (DFDs).
- **Implementation**: Developed both front-end and back-end functionality, including Java code, servlets, and database connectivity.
- **Testing**: Comprehensive testing was done to ensure the system operates efficiently under various conditions, focusing on privacy and social utility balance.

## How to Run the Project

1. **Install Java and Tomcat Server**: Ensure you have Java and Apache Tomcat installed on your system.
2. **Set Up MySQL Database**: Import the SQL database file to set up the required tables.
3. **Clone the Repository**: Clone or download the repository to your local machine.
4. **Deploy on Tomcat Server**: Deploy the project on the Tomcat Server and run it in your web browser.
5. **Access the Application**: You can access the system as an admin or user, register, and explore the features.

## Conclusion

This project highlights the balance between privacy and social utility in Cyber-Physical Social Systems. By utilizing Java, MySQL, and privacy preservation algorithms, the system allows users to actively engage in social interactions while maintaining control over their sensitive physical profiles.

