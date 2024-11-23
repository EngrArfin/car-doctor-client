# Car Doctor Client

This project is the client-side of the **Car Doctor** application, a web platform for managing car maintenance and repair services. The application provides seamless interactions for users to browse services, book appointments, and view repair details.

## Live Demo

Check out the live project here: [Car Doctor Client](https://mohammadpur-hospital-magura.netlify.app)

## GitHub Repository

The project repository is available on GitHub: [Car Doctor Client](https://github.com/EngrArfin/car-doctor-client)

## Features

- User-friendly interface for managing car repair bookings.
- Authentication and authorization for secure user sessions.
- View and search for car maintenance services.
- Book services with real-time updates.
- Responsive design for all device sizes.

  
## Folder Structure
```bash
src/
├── components/       # Reusable UI components
├── pages/            # Application pages
├── hooks/            # Custom React hooks
├── services/         # API and Firebase interactions
├── styles/           # Global and modular CSS
└── App.js            # Main app component

```


## Technologies Used

### Frontend
- **React**: For building the user interface.
- **HTML5**: For structuring the webpage.
- **CSS3**: For styling the application.
- **JavaScript**: For adding interactivity.

### Backend
- **Node.js**: For server-side programming.
- **Express**: For handling server-side routing and API creation.

### Database
- **MongoDB**: For storing application data.

### Authentication
- **Firebase**: For user authentication and authorization.

## Installation and Setup

Follow the steps below to set up the project locally:

1. **Clone the repository:**

```bash
  git clone https://github.com/EngrArfin/car-doctor-client.git
   cd car-doctor-client
```

 2. **Install dependencies: Make sure you have Node.js installed. Then, run:

```bash
  npm install
```
3. **Configure Firebase:

Create a Firebase project at Firebase Console.
Add your Firebase configuration to a .env file in the root of the project:

```bash
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```

4. **Install dependencies: Make sure you have Node.js installed. Then, run:

```bash
  npm start dev
```







