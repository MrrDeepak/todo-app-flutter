# TODO APP

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Intro
Welcome to the Todo App! This Flutter project demonstrates how to build a simple task management application that integrates with a REST API. Users can add, delete, and edit todo items through the app, showcasing practical use of Flutter for managing state and interacting with backend services.

# Features
* Add Todo: Users can create new todo items.
* Edit Todo: Users can update existing todo items.
* Delete Todo: Users can remove todo items from the list.
* REST API Integration: Communicates with a REST API to manage todo data.
* State Management: Demonstrates state management for syncing UI with API responses.

# Getting Started
To get started with the Todo App, follow these steps:

## Prerequisites
Ensure you have the following installed:
* Flutter SDK: Installation Guide
* Dart SDK: Included with Flutter SDK
* An IDE such as Visual Studio Code or Android Studio

#Installation
1. Clone the repository:
```
git clone https://github.com/yourusername/todo-app-flutter.git
```
2. Navigate to the Flutter project directory:
```
cd todo-app-flutter
```
3. Install dependencies:
```
flutter pub get
```
4. Run the application:
```
flutter run
```
This will launch the app on your connected device or emulator.

# Project Structure
* lib/: Contains the main code for the app.
* main.dart: Entry point of the application.
* screens/: Contains different screen implementations for listing, adding, editing, and deleting todos.
* models/: Contains data models for todo items.
* services/: Contains API service for interacting with the REST API.
* widgets/: Contains custom widgets used throughout the app.
* assets/: Contains any assets like images or fonts used in the app.
* pubspec.yaml: Lists the dependencies and assets for the project.

# API Endpoints
The Todo App communicates with a REST API that supports the following endpoints:
* GET /todos: Retrieve the list of todos.
* POST /todos: Create a new todo item.
* PUT /todos/{id}: Update an existing todo item.
* DELETE /todos/{id}: Delete a todo item.
Ensure your API supports these endpoints and is properly configured to handle the requests.

# License
This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/license/mit) file for details.

# Screenshots
![Screenshot 2024-08-17 130252](https://github.com/user-attachments/assets/621edd0d-ac92-4b57-8645-58f15de250cd)
![Screenshot 2024-08-17 130314](https://github.com/user-attachments/assets/27729c27-3632-4356-ba14-5d86c8708de9)







