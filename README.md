# CSV Upload Project

Welcome to the CSV Upload Project! This web application allows users to upload CSV files and view their content in a tabular form. The application is hosted at [CSVUpload](https://csvupload-7j3v.onrender.com).

## File Structure

```
📂 CSV Upload Project
├── assets
│   ├── css
│   │   └── [css files]        # CSS files for frontend styling
│   └── js
│       └── [js file]          # JS files for frontend functionality
├── config
│   └── mongoose.js            # MongoDB configuration file
├── controllers
│   ├── file_controller.js     # Controller for handling file upload and deletion
│   └── home_controller.js     # Controller for rendering home and file viewer pages
├── models
│   └── csv.js                 # Mongoose model for storing uploaded CSV files
├── routes
│   └── index.js               # Application routes and controller mappings
├── uploads
│   └── files                  # Directory to store uploaded CSV files
│       └── [uploaded files]
├── views
│   ├── file_viewer.ejs        # EJS file for displaying uploaded file content
│   └── home.ejs               # EJS file for rendering the home page
├── index.js                   # Main application entry point
├── package.json               # Project dependencies and scripts
├── package-lock.json          # Detailed information about project dependencies
└── README.md                  # Project documentation

```

## Project Overview

### assets
This directory contains the CSS and JS files used for frontend styling and functionality.

### config
The `mongoose.js` file contains the configuration for connecting to the MongoDB database using Mongoose.

### controllers
The `file_controller.js` and `home_controller.js` files contain the logic for handling file uploads, viewing uploaded files, and other actions related to file management.

### models
The `csv.js` file defines the Mongoose model for storing information about the uploaded CSV files in the database.

### routes
The `index.js` file defines the routes for the application, mapping URLs to the corresponding controller functions.

### uploads
This directory is used to store the uploaded CSV files.

### views
This directory contains the EJS (Embedded JavaScript) files used for frontend rendering and displaying the uploaded files.

### index.js
The main entry point of the application that sets up the server, connects to the database, and handles route initialization.

## Installation and Usage

1. Clone the repository from [GitHub](https://github.com/iamshivanshyadav/CSVUpload).
2. Navigate to the project directory in the terminal.
3. Run `npm install` to install the required dependencies.
4. Make sure you have MongoDB installed and running on your system.
5. Create a `.env` file and set the environment variables (if required) for configuration.
6. Start the application using `npm start`.
7. Open a web browser and navigate to [CSVUpload](https://csvupload-7j3v.onrender.com).
8. Upload CSV files and enjoy exploring the content!

## Contributing

Contributions to this project are welcome! If you find any bugs or want to add new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
