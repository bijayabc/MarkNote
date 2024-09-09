# Note-Taking App

A simple and responsive note-taking application built with React and Firebase. This app allows users to create, update, and delete notes with real-time synchronization using Firestore.

## Features

- **Real-time Sync**: Notes are synchronized in real-time using Firebase Firestore.
- **Markdown Support**: Write and format your notes using Markdown.
- **Responsive Design**: Built to work seamlessly on both desktop and mobile devices.
- **Create, Update, and Delete Notes**: Manage your notes effortlessly.

## Technologies

- **React**: For building the user interface.
- **Firebase**: For real-time database and authentication.
- **react-split**: For creating resizable and draggable panels.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```

2. **Navigate into the project directory:**

    ```bash
    cd your-repo-name
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

4. **Set up Firebase:**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Add your Firebase configuration to the `firebase.js` file.

5. **Start the development server:**

    ```bash
    npm start
    ```

    Your app should now be running at `http://localhost:3000`.

## Usage

- **Creating Notes**: Click on the "Create one now" button to add a new note.
- **Editing Notes**: Select a note from the sidebar to start editing it.
- **Deleting Notes**: Click the delete button next to the note you wish to remove.

