

# Blog with Database – Starting Files

This project serves as a foundational template for building a dynamic blog application using Node.js, Express, EJS templating, and MongoDB. It provides a structured starting point for developers to implement features such as creating, reading, updating, and deleting blog posts.

## Features

* Server-side rendering with EJS templates
* Routing with Express.js
* MongoDB integration for data persistence
* Modular code structure for scalability

## Getting Started

### Prerequisites

* [Node.js](https://nodejs.org/) (version 14 or higher)
* [MongoDB](https://www.mongodb.com/) (local or cloud instance)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/MurtadhaJasim/Blog-with-Database.git
   cd Blog-with-Database-Starting-Files
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following:

   ```env
   PORT=3000
   MONGODB_URI=your_mongodb_connection_string
   ```

4. **Start the application:**

   ```bash
   npm start
   ```

5. **Open your browser and navigate to:**

   ```
   http://localhost:3000
   ```

## Project Structure

```
Blog-with-Database-Starting-Files/
├── public/
│   └── css/
│       └── styles.css
├── views/
│   ├── partials/
│   └── pages/
├── app.js
├── package.json
└── README.md
```



## Technologies Used

* [Node.js](https://nodejs.org/)
* [Express.js](https://expressjs.com/)
* [EJS](https://ejs.co/)
* [MongoDB](https://www.mongodb.com/)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Submit a pull request

## License

This project is licensed under the [MIT License](LICENSE).

