# Opinion

Application built using Node.js, Express, and EJS. The application allows users to create, read, update, and delete (CRUD) posts. Each post contains a username and content, and the posts are displayed in a simple interface.

## Features

- **View All Posts:** Users can view a list of all posts.
- **Create a New Post:** Users can create a new post by providing a username and content.
- **View Post Details:** Users can view the details of a specific post.
- **Edit Post:** Users can edit the content of an existing post.
- **Delete Post:** Users can delete a post.

## Project Structure

- **`views/`**: Contains EJS templates for rendering the UI.
  - `index.ejs`: Displays all posts.
  - `new.ejs`: Form for creating a new post.
  - `show.ejs`: Displays details of a specific post.
  - `edit.ejs`: Form for editing an existing post.
- **`public/`**: Contains static files such as CSS for styling.
  - `style.css`: Basic styling for the application.
- **`index.js`**: The main server file that handles routing.

## Technologies Used

- **Node.js**: JavaScript runtime environment.
- **Express**: Web application framework for Node.js.
- **EJS**: Embedded JavaScript templating engine.
- **method-override**: Middleware for overriding HTTP methods (used for PATCH and DELETE).
- **uuid**: Library for generating unique IDs.

## Installation

1. Clone the repository:
   ```bash
   git clone git@github.com:jhasachi/Opinion.git
2. **Navigate to the project directory:**
    ```bash
     cd Opinion
3. **Install the dependencies:**
    ```bash
    npm install
4. **Start the server:**
    ```bash
   node index.js
5.	Open your browser and navigate to http://localhost:8080 to view the application.

## Future Enhancements

- **Improved Styling**: The current UI is basic, but I plan to enhance it with better styling and a more modern design in the future.
- **User Authentication**: Implement user authentication to allow users to log in and manage their own posts.
- **Database Integration**: Replace the in-memory storage with a database like MongoDB for persistent data storage.
