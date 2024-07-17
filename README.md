# Training and Placement Database Management System

## Overview

This Training and Placement Database Management System is designed for educational institutions to efficiently manage student profiles, company information, training records, and placement details. It provides separate interfaces for administrators and students, streamlining the placement process.

## Features

- User authentication (admin and student logins)
- Student profile management 
- Company information management
- Training record tracking
- Placement record tracking
- Report generation (training and placement reports)
- Course and branch information management

## Technologies Used

- Java Swing for GUI
- MySQL for database
- JDBC for database connectivity

## Setup and Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/training-placement-system.git
   ```

2. Install Java Development Kit (JDK) if not already installed

3. Install MySQL database

4. Set up the database:
   - Create a new database named `tps_db`
   - Import the provided SQL schema file

5. Configure database connection:
   - Open `src/Connect.java`
   - Update the connection string, username, and password if necessary

6. Compile and run the application:
   ```
   javac -cp .:mysql-connector-java.jar src/*.java
   java -cp .:mysql-connector-java.jar src.MainApplication
   ```

## Usage

1. Launch the application
2. Log in as an admin or student
3. Navigate through the menu to access various features

## Screenshots

![image](https://github.com/user-attachments/assets/6407ece8-f58f-4159-88db-6f65e11b0954) #login page 
![image](https://github.com/user-attachments/assets/983010b4-4134-41d2-b1b1-5a251726707b) #Main window
![image](https://github.com/user-attachments/assets/b539e04a-c648-4eb9-9237-8ab305fd8bfc) #Student portal
![image](https://github.com/user-attachments/assets/f1de6273-9b94-4e3e-98d6-8a6934ee7e52) #Course entry window
![image](https://github.com/user-attachments/assets/0ea44804-feee-4aec-96e0-fae692a91205) #Company entry window
![image](https://github.com/user-attachments/assets/9ac10e68-c322-4ad4-aa03-af3158c3de69) #Students profile entry window
![image](https://github.com/user-attachments/assets/fb1135bd-8b51-46ff-a380-b86089dfee7f) #Students training window
![image](https://github.com/user-attachments/assets/a8be83cf-3743-4ff1-88e9-73802a36d1ba) #Students placement window
![image](https://github.com/user-attachments/assets/997b1940-1f22-43ed-87de-5550823e7395) #Students training report window
![image](https://github.com/user-attachments/assets/06b8bf31-7386-41aa-b08a-2b3003517cba) #Students placement report window
![image](https://github.com/user-attachments/assets/36085daf-b03c-48f7-921d-a1997a050c90) #About window
![image](https://github.com/user-attachments/assets/e8bc5ad4-5089-47d1-bfd4-4662e9ab233e) #Contact window










## Contributing

Contributions to improve the system are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgements

- Dr. R. SARAVANA KUMAR (Assistant Professor, Dept. of CSE) for project guidance
- Visvesvaraya Technological University for the project opportunity

## Contact

Manikanta- Maniii0409@gmail.com

Project Link: [https://github.com/your-username/training-placement-system](https://github.com/your-username/training-placement-system)
