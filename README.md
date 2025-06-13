# Distributed Storage Application

This is a cross-platform distributed storage application built with Flutter for the frontend and Node.js for the backend.

## Project Structure

The project consists of two main components:

1. **Frontend (Flutter App)** - Located in the [distributed_storage_app](distributed_storage_app) directory
   - Cross-platform mobile and desktop application
   - Supports Android, iOS, Windows, macOS, Linux, and Web

2. **Backend (Node.js)** - Located in the [distributedStorage](distributedStorage) directory
   - RESTful API server
   - Database connectivity

## Setup Instructions

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Node.js](https://nodejs.org/)
- Android Studio (for Android development)
- Xcode (for iOS/macOS development)
- Visual Studio (for Windows development)

### Frontend Setup

1. Navigate to the Flutter app directory:
cd distributed_storage_app

2. Install dependencies:
flutter pub get

### Backend Setup

1. Navigate to the Node.js backend directory:
cd distributedStorage

2. Install dependencies:
npm install

3. Set up environment variables:
- Create a `.env` file based on the existing sample

4. Initialize the database:
node initDb.js

## Running the Application

### Backend

1. Start the backend server:
cd distributedStorage node app.js

### Frontend

1. Run the Flutter app:
flutter run
