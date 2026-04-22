🏋️‍♂️ EFC Booking System

A Java-based application designed to manage fitness class bookings efficiently. This system allows users to view schedules, book sessions, manage members, and handle feedback in a structured way.

📌 Features
📅 View fitness class schedules
🧑 Manage member information
📝 Book and cancel class sessions
⏱️ Time slot management
📊 Booking status tracking
💬 Feedback handling
🧪 Unit testing support
🏗️ Project Structure
EFC/
│── src/
│   ├── main/java/efc/
│   │   ├── model/        # Data models (Booking, Member, Schedule, etc.)
│   │   ├── service/      # Business logic (BookingManager)
│   │   ├── ui/           # User interface (FitnessUI)
│   │   ├── data/         # Initial data setup (DataSeeder)
│   │   └── Main.java     # Entry point
│   │
│   ├── test/java/efc/
│   │   └── EFCSystemTest.java  # Test cases
│
│── pom.xml               # Maven configuration
⚙️ Technologies Used
Java
Maven
JUnit (for testing)
🚀 Getting Started
Prerequisites
Java JDK (8 or above)
Maven installed
Installation & Run

Clone the repository:

git clone https://github.com/your-username/efc-booking-system.git

Navigate to the project folder:

cd efc-booking-system

Build the project:

mvn clean install

Run the application:

mvn exec:java -Dexec.mainClass="efc.Main"
🧩 Core Components
📦 Models
Booking
Member
Schedule
ClassSession
TimeSlot
Feedback
BookingStatus
🔧 Service Layer
BookingManager
Handles all booking operations and business logic.
🖥️ UI
FitnessUI
Provides interaction with users.
🗄️ Data Seeder
DataSeeder
Initializes sample data for testing/demo.
🧪 Testing

Run tests using:

mvn test
📈 Future Enhancements
Web-based UI (Spring Boot / React)
Database integration (MySQL/PostgreSQL)
Authentication & user roles
Real-time booking updates
🤝 Contributing

Contributions are welcome!

Fork the repo
Create a new branch
Commit your changes
Submit a pull request
📜 License

This project is for educational purposes. You can modify and use it as needed.

