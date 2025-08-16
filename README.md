# Own API for Blog Practice

A practice project to build your own blog API using JavaScript, Express, and EJS. This API enables basic CRUD (Create, Read, Update, Delete) operations on blog posts and serves as a hands-on learning tool for creating server-side applications for blogging.

## About

This project is designed to help you practice building a full-stack-capable blog API. You'll get to work with backend logic for creating, reading, updating, and deleting blog entries, along with a simple frontend using EJS for templating.

## Features

- Add, view, edit, and delete blog posts
- API endpoints for seamless interaction
- Simple server-rendered views with EJS
- Practice setting up and configuring Express.js

## Tech Stack

- **Node.js** – JavaScript runtime environment
- **Express.js** – Fast, minimal web framework
- **EJS** – Template engine for rendering views
- **CSS** – Basic styling for frontend

## Project Structure
```
own-API-for-a-blog-practice/
├── public/
│ └── styles/ # Static CSS files
├── views/ # EJS template files
├── index.js # Entry point (or)
├── server.js # Express server setup
├── solution.js # Additional logic or route handling
├── package.json # NPM scripts and dependencies
├── package-lock.json # Lock file for dependencies
└── README.md # You’re reading it!

```

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/pawanthathsara987/own-API-for-a-blog-practice.git
   cd own-API-for-a-blog-practice
   ```

2. **Install Dependencies**:
   ```bash
   npm install  # If using Node.js
   # OR
   pip install -r requirements.txt  # If using Python
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add the following:
   ```env
   DATABASE_URL=your_database_connection_string
   PORT=3000
   # Add other environment variables as needed
   ```

4. **Run the Application**:
   ```bash
   npm start  # If using Node.js
   # OR
   python app.py  # If using Python
   ```

## API Endpoints
| Method | Endpoint              | Description                     |
|--------|-----------------------|---------------------------------|
| GET    | `/api/posts`          | Retrieve all blog posts         |
| GET    | `/api/posts/:id`      | Retrieve a single post by ID    |
| POST   | `/api/posts`          | Create a new blog post          |
| PUT    | `/api/posts/:id`      | Update an existing blog post    |
| DELETE | `/api/posts/:id`      | Delete a blog post              |


## Testing
- Use tools like Postman or cURL to test the API endpoints.
- Run automated tests (if implemented):
  ```bash
  npm test  # If using Node.js
  # OR
  pytest  # If using Python
  ```

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or suggestions, feel free to reach out:
- GitHub: [pawanthathsara987](https://github.com/pawanthathsara987)
- Email: [pawanthathsara987@gmail.com]
