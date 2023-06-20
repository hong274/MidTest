Ensure you have Node.js and npm (Node Package Manager) installed on your machine.

Create a new directory for your project and navigate to that directory in your terminal or command prompt.

Create a new file called package.json in the project directory by running the following command:

csharp
Copy code
npm init -y
Install the required dependencies (Express and Mongoose) by running the following command:

Copy code
npm install express mongoose
Create a new file called app.js (or any other preferred name) in the project directory.

Copy and paste the provided code into the app.js file.

Start your MongoDB server. If MongoDB is not installed, please install it and make sure it is running.

Modify the MongoDB connection URL in the code if necessary. By default, it is set to connect to the MongoDB server running on mongodb://127.0.0.1:27017/studentInfo. If your MongoDB server is running on a different host or port, update the URL accordingly.

Save the app.js file.

Run the Node.js application by executing the following command in the terminal or command prompt:

Copy code
node app.js
If everything is set up correctly, you should see the message "Connected to MongoDB" and "Server is listening on port 3000" in the console, indicating that the server is running successfully.

You can now use Postman or any other API testing tool to send requests to the server endpoints, such as GET, POST, PUT, and DELETE requests to the appropriate URLs (e.g., http://localhost:3000/studentInfo).

Note: Make sure to replace the URL and HTTP method (e.g., GET, POST, etc.) based on the desired operation.