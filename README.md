# proctor_test
This is a simple web application that allows users to upload images and view them in a gallery. It consists of three parts:

1. A frontend web page written in HTML, CSS, and JavaScript that allows users to input a user ID and retrieve all images associated with that user ID.
2. A backend server written in Node.js using the Express.js framework that provides a RESTful API for creating and retrieving users and images.
3. A SQLite database to store user and image data.

## How To Use
### Prerequisites
- Node.js installed on your computer. 
* A modern web browser such as Google Chrome, Mozilla Firefox, or Microsoft Edge.

### Installation
1. Clone or download this repository.
2. Navigate to the root directory of the project in a terminal or command prompt.
3. Run npm install to install the project's dependencies.
### Usage
1. Start the server by running node server.js in a terminal or command prompt.
2. Open a web browser and navigate to http://localhost:3000.
3. Use the form on the page to input a user ID and retrieve images associated with that user ID.
## Code Overview
### Frontend Web Page
The frontend web page is a simple HTML form that allows users to input a user ID and retrieve images associated with that user ID. It contains a JavaScript function that makes an asynchronous HTTP request to the backend server to retrieve image data, and then dynamically updates the page with the retrieved image data.

### Backend Server
The backend server is a Node.js application that uses the Express.js framework to provide a RESTful API for creating and retrieving users and images. It uses the Multer middleware to handle image uploads, and the SQLite database to store user and image data.

### SQLite Database
The SQLite database is used to store user and image data. It consists of two tables: users and images. The users table contains information about each user, including their name, email address, and user ID. The images table contains information about each image, including the user ID of the user who uploaded the image, the filename of the image, and the upload time of the image.

### Conclusion
This is a simple example of how to build a web application that allows users to upload and view images. With some additional work, this application could be expanded to include additional features such as user authentication, image tagging, and more.

### PS
I am not very comfortable with chrome Extension but I have tried to make one in the file Image-gallery_extension and currently learning and working on it
