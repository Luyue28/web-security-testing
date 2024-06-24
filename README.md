# Basic CRUD

This project demonstrates a basic CRUD (Create, Read, Update, Delete) operation. It allows users to create, edit, and delete content dynamically through a user-friendly interface. The primary goal of this project is to practice using Docker and deploying projects. Therefore, only the most basic CRUD operations are designed.

## Technologies Used

- **PHP**
- **Laravel**

## Setup and Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/Luyue28/web-security-testing.git
   cd path/to/your/project/directory
   ```
2. **Install dependencies:**

   ```sh
   composer install
   npm install
   npm run dev
   ```
3. **Configure environment:**
   Copy the `.env.example` file to `.env` and update your database and other configurations.

   ```sh
   cp .env.example .env
   php artisan key:generate
   ```
4. **Run migrations:**

   ```sh
   php artisan migrate
   ```
5. **Start the application:**

   ```sh
   php artisan serve
   ```
6. **Access the application:**
   Open your browser and go to `http://localhost:8000`

## Author

This project was created by **Luyue Zhang**, a first-year ICT student at HZ University of Applied Sciences. It is part of a school assignment.

## License

This project is open-source and available under the [MIT License](LICENSE).
