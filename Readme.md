
# ALU Assistant – Mobile Application

## Overview

ALU Assistant is a Flutter-based mobile application designed to help African Leadership University (ALU) students manage their academic responsibilities more effectively. The application serves as a personal academic assistant by enabling students to organize assignments, schedule academic sessions, and monitor their academic engagement and attendance throughout the semester.

The project was developed as part of an academic assignment to identify a common student challenge and propose a practical, technology-driven solution.


## Features

### 1. Authentication

* User registration and login system.
* Ensures only authenticated users can access the main application features.
* Simple credential validation implemented using a dedicated authentication service.

### 2. Dashboard

* Displays the current academic week.
* Shows a list of today’s scheduled academic sessions.
* Provides a quick overview of the student’s academic activity.

### 3. Assignment Management

* Create new assignments with relevant details.
* Edit assignment information when changes occur.
* Remove assignments when they are no longer needed.
* View all assignments in a structured list.

### 4. Academic Session Scheduling

* Schedule sessions with start date, end date, and location.
* Modify session details when arrangements change.
* Remove sessions when they are cancelled.
* View scheduled academic sessions in an organized format.

### 5. Attendance Tracking

* Maintain attendance history for academic sessions.
* Track attendance metrics.
* Display alerts when attendance falls below a defined threshold.

### 6. Navigation and User Interface

* Bottom navigation bar for easy access to Dashboard, Assignments, and Schedule.
* Consistent layout across all screens.
* User interface aligned with ALU branding and color palette.
* Clear labeling of all form fields and actions.


## Technology Stack

* Flutter: Used for building the mobile user interface.
* Dart: Used for application logic and state management.
* Material Design: Used for UI components and layout structure.


## Project Structure

The project is organized into multiple folders to improve readability and maintainability:

* auth: Contains login and registration screens.
* screens: Contains main application screens such as Dashboard, Assignments, and Schedule.
* services: Contains service classes such as authentication logic.
* main.dart: Entry point of the application and main navigation setup.

This modular structure ensures separation of concerns and allows the application to scale easily with new features.


## Setup and Installation

1. Clone the repository or download the project files.
2. Open the project folder in Visual Studio Code.
3. Ensure Flutter and Dart are installed and properly configured.
4. Run the following commands in the terminal:

```bash
flutter pub get
flutter run
```

5. Launch the app on an emulator or physical device.


## Usage

1. Register a new account using the registration screen.
2. Log in using your credentials.
3. Navigate through the app using the bottom navigation bar.
4. Add, edit, or remove assignments as needed.
5. Schedule academic sessions and update them when changes occur.
6. Monitor attendance and respond to alerts when attendance drops below the defined threshold.


## Future Improvements

* Persistent data storage using a local database or cloud services.
* Integration with external academic platforms.
* Push notifications for assignment deadlines and upcoming sessions.
* User profile management.
* Cloud-based authentication and synchronization across devices.


## Contributors

* Benigne Uwitonze
* Delucie Rurangwa
* Bakhit Tidjani Mahamat
* Jolly Gift Burabyo