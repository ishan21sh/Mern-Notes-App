# MERN Notes Application

Welcome to the MERN Notes Application! This is a full-stack notes application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It provides users with the ability to register, log in, and manage their personal notes securely. JSON Web Tokens (JWT) are used for user authorization, ensuring data privacy and security.

## Features

- User Registration: Create an account to access the notes application.
- User Login: Log in securely using your registered credentials.
- Note Management: Create, read, update, and delete your personal notes. Each note includes a creation date.
- JSON Web Token (JWT) Authorization: Ensures data privacy and secure access to user-specific features.
- Main Dashboard: After successful login, users are directed to the main page where they can manage their notes.

## Tech Stack

- Frontend: React.js with Material-UI (MUI)
- Backend: Node.js with Express.js
- Database: MongoDB
- Authentication: JSON Web Tokens (jsonwebtoken)

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js: [Download and install Node.js](https://nodejs.org/)
- MongoDB: [Download and install MongoDB](https://www.mongodb.com/try/download/community)

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/ishan21sh/mern-notes-app.git
```

2. Navigate to the project directory:

```bash
cd Mern-Notes-App
```

3. Install server dependencies:

```bash
npm install
```

4. Navigate to the client directory:

```bash
cd client
```

5. Install client dependencies:

```bash
npm install
```

6. Return to the project directory:

```bash
cd ..
```

7. Create a `.env` file in the project root and add the following configuration:

```
MONGODB_URI=your_mongodb_connection_string
SECRET_KEY=your_secret_key_for_jwt
```

Replace `your_mongodb_connection_string` with your actual MongoDB connection string and `your_secret_key_for_jwt` with a secret key for JWT token generation.

## Usage

1. Start the server:

```bash
npm run server
```

2. In a separate terminal, start the client:

```bash
npm run client
```

3. The application will open in your default browser. If not, you can access it at [http://localhost:3000](http://localhost:3000).

4. Register a new user account using the registration page.

5. Log in using your registered credentials.

6. After successful login, you will be directed to the main dashboard where you can manage your notes.

## Main Dashboard Functionalities

- **Add a New Note:** Click on the "Add Note" button to create a new note. Provide the title and content for your note and click "Save." The creation date will be automatically recorded.

- **View All Notes:** On the main dashboard, you will see a list of all your existing notes. Click on a note to view its details, including its creation date.

- **Delete an Existing Note:** To delete a note, click the "Delete" button next to the note you want to remove. Confirm the action to delete the note permanently.

- **Update an Existing Note:** To edit a note, click the "Edit" button next to the note. Update the title and content and click "Save" to update the note. You can also change the creation date if needed.

- **Log Out:** When you're done using the application, you can log out by clicking the "Log Out" button. This will securely end your session.

## Contributing

We welcome contributions to improve the MERN Notes Application. If you find any bugs or want to add new features, feel free to submit a pull request. Please review our [Contribution Guidelines](CONTRIBUTING.md) for more information.

