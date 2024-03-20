## Realtime Collaborative Document Editor with Google Sign-In (Flutter & Node.js)

This projectis about building a real-time collaborative document editor application from scratch.

**Features:**

* User Authentication with Google Sign-In (without Firebase)
* Persistent Login Management
* Rich Text Editor for document creation and editing
* Responsive Design
* Create new documents
* View document list by user
* Update document titles
* Share document links for collaborative editing (multiple users)

**Technologies Used:**

* Flutter
* Node.js
* Express.js
* Socket.IO
* MongoDB
* Riverpod

**Setup:**

1. Clone this repository.
2. Install Flutter and Node.js according to their official installation guides.
3. Run `flutter pub get` in the project directory to install Flutter dependencies.
4. Navigate to the backend directory (e.g., `server`) and run `npm install` to install Node.js dependencies.
5. Configure the database connection details in the backend code (refer to MongoDB connection setup documentation).

**Running the Application:**

1. Start the backend server (e.g., `node server.js`).
2. Run the Flutter application (e.g., `flutter run`).

**Disclaimer:**

This project implements Google Authentication without Firebase. While it offers more control, it might require additional security considerations compared to Firebase's managed solution.

**Contributing:**

Pull requests and suggestions are welcome!
