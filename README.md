# Express.JS CRUD App

# 👉Description

   This Express CRUD App serves as a practical example of building a RESTful API using Node.js and Express . It provides users with the ability to create,read,update and delete items in a straightforward manner. The application is designed to be lightweight and easy to understand ,making it an excellent starting point for developers looking to learn about Express and RESTful principles.

### For a CRUD API , you typically need four types of operations:

👉 Create (POST): Adds new data.

👉Read(GET): Retrives data.

👉Update(PUT,PATCH): Modifies existing data.

👉Delete(DELETE): Removes data.

### A small video to show how it's works.

https://github.com/user-attachments/assets/11ae5bd4-e3b3-4b08-b6a9-c306b62e7815

### Installing Node.js and npm

- After installing Node.js and npm , You should check your version . for that type the command on your terminal or command prompt:

![Screenshot 2024-09-24 011147](https://github.com/user-attachments/assets/a99240e8-d130-42a4-ab31-d4bfd2a2298b)

- Now you should see the version number of npm.

### Installing Express and Other Necessary Packages

- Express is a web application framework for Node.js. It simplifies server creation and routing. You can Install Express by running:


![Screenshot 2024-09-24 011751](https://github.com/user-attachments/assets/36657153-53b6-409f-9111-7a3202ea8cde)

This command add express to your projrct.

# Now make a file and name that file as server.js

![Screenshot 2024-09-24 014134](https://github.com/user-attachments/assets/0c5b1893-faa3-48b5-a736-4b2eb91a484a)

- To start the server file u have to open your terminal or command prompt and run :

![Screenshot 2024-09-24 012311](https://github.com/user-attachments/assets/15aa6490-7fae-4ffb-85d2-3503f021d501)

- Now Open your web browser and go to http://localhost:3000. You should see ‘Hello World!’ displayed.

# Implementing CRUD Operations
### Create: Adding a New Book
- First, you’ll need to handle JSON data.At the top of your server.js, add:

![Screenshot 2024-09-24 015447](https://github.com/user-attachments/assets/0018c7ef-caf4-4257-a693-d1b13c4fe827)

This line tells Express to parse JSON data in incoming requests.
### To create a book you should add:

![Screenshot 2024-09-24 020303](https://github.com/user-attachments/assets/84ae832c-30bb-4087-b80f-092b85d24f57)

### Now to get all books you should add:

![Screenshot 2024-09-24 020339](https://github.com/user-attachments/assets/072e5da7-44a2-4505-a9ae-026ec6bf01be)

### Again to get book by id you should add:

![Screenshot 2024-09-24 020354](https://github.com/user-attachments/assets/5551bc97-e424-496c-9530-d74a3d990ccd)

### After that to update book you should add the code:

![Screenshot 2024-09-24 020503](https://github.com/user-attachments/assets/5fe4e615-0ae4-410d-89f2-3942e754692d)

### At last to delete a code you should add the code i.e:

![Screenshot 2024-09-24 020519](https://github.com/user-attachments/assets/bc8013f6-0fa8-4e4c-8149-a2dd4175d59c)

- And there you have it. You’ve implemented all the CRUD operations for your book management API.

# Integrating a Database;
- Let’s integrate a database into your application. For this example, let’s use MongoDB.

### Installing Mongoose
- For installing mongoose you should add a command in your terminal or comand prompt:

![Screenshot 2024-09-24 022508](https://github.com/user-attachments/assets/468f64e2-5369-4e65-93f6-f5cc5a11288b)

# Creating a model
- With Mongoose, you define your data structure through schemas. Let’s create a schema for your books.

- Create a new file named bookModel.js in your project directory and add the following:

![Screenshot 2024-09-24 023203](https://github.com/user-attachments/assets/4e302316-0d36-492b-bcaa-15d18e2d9bb5)
