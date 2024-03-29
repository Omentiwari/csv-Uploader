# csv-Uploader
CSV Upload File Backend
This project is a CSV file upload system built using Node.js, EJS, CSS, and JavaScript. It's designed to be responsive across all devices.

## Features
File Upload: Users can upload CSV files into the system using Multer JS. File Management: Displays a list of all uploaded CSV files. Each file is parsed, converted into JSON, and stored in a Mongo Database. Data Display: Upon selecting a file, it displays all the data (with column headers) in a table on the frontend. Search Functionality: Includes a search box that filters and displays matching rows in the table based on user input. An empty search box displays all the data. Sorting: Enables sorting functionality (ascending and descending) for each column in the table. File Type Validation: Provides validation both on the frontend and server-side, allowing only CSV file uploads. Pagination: Implements pagination for the displayed table data, limiting it to a maximum of 100 records per page.

Hosted Link - https://csv-uploader-kf89.onrender.com

$ npm install 
Start the application using the following command:

$ npm start 
Open the application in your web browser by visiting the following URL:

$ http://localhost:8000 
Features
CSV file upload: Users can upload CSV files with a simple web form.
CSV parsing: The application parses the CSV data and displays it in a table.
Searching: Users can search data in the table.
API Reference
CSV_Upload provides a simple API for uploading and parsing CSV files. The API supports the following endpoints:

POST /upload: Uploads a CSV file and parses the data.
GET /data: Returns the parsed CSV data as JSON.
Folder Structure
CSV_Upload/
|── |assets/
│   |      ├── css/
│   │      |     ├── styles.css
│   |      ├── js/
│   |            ├── script.js
│   ├── uploads/
│   ├── index.html
|   |
├── routes/
│   ├── csvRoutes.js
|   |
├── controllers/
│   ├── csvController.js
|   |
├── models/
│   ├── csvModel.js
|   |
├── .gitignore
├── package.json
├── README.md
