# Codergangs Project 

# Codergangs

## Project Setup  
Codergangs/  
├── client/                  # Frontend application  
│   ├── public/              # Static assets (images, icons)  
│   ├── src/                 # Main source code  
│       ├── assets/          # Images, fonts, etc.  
│       ├── components/      # Reusable UI components  
│       ├── pages/           # Application pages (Home, Courses)  
│       ├── layouts/         # Page layouts (header, footer)  
│       ├── hooks/           # Custom React hooks  
│       ├── services/        # API calls and services  
│       ├── utils/           # Utility functions  
│       ├── context/         # Context for global state management  
│       └── routes/          # Route definitions and navigation  
├── server/                  # Backend application  
│   ├── src/                 # Main source code  
│       ├── config/          # Configuration files (DB, environment)  
│       ├── controllers/     # Handle HTTP requests and responses  
│       ├── models/          # Database models (User, Course)  
│       ├── routes/          # API endpoints  
│       ├── middlewares/     # Request handling middlewares  
│       ├── services/        # Business logic  
│       └── utils/           # Utility functions for server  
├── database/                # Database-related files (migrations, seeders)  
├── .env                     # Environment variables  
├── .gitignore               # Files and folders to ignore in Git  
├── README.md                # Project documentation  
└── package.json             # Project dependencies  
 




## Purpose of Key Files  
- **client/src/App.js:** Main application file for rendering components.  
- **client/src/index.js:** Entry point to render the app to the DOM.  
- **server/src/server.js:** Entry point for the backend server.  
- **.env:** Store environment variables securely.  
- **.gitignore:** Specifies files and directories to ignore during version control.  
- **README.md:** Documentation and setup instructions for the project.  
- **package.json:** Manages project dependencies and scripts.  

 






## Setup Commands  
To set up the project structure, the following commands were used:  

### Windows Command Prompt  
```cmd
mkdir client client\public client\src client\src\assets client\src\components client\src\pages client\src\layouts client\src\hooks client\src\services client\src\utils client\src\context client\src\routes  
mkdir server server\src server\src\config server\src\controllers server\src\models server\src\routes server\src\middlewares server\src\services server\src\utils  
mkdir database  
echo. > .env  
echo. > .gitignore  
echo. > README.md  
echo. > package.json  
echo. > client\src\App.js  
echo. > client\src\index.js  
echo. > server\src\server.js  
echo Node_modules/ > .gitignore  
echo # Codergangs Project > README.md  

