# MovieTicketBookingSystem

Welcome to the MovieTicketBookingSystem project! This project is a web-based application developed to facilitate the online booking of movie tickets. It is built using Core PHP, HTML, JavaScript, CSS, and Bootstrap.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

The MovieTicketBookingSystem is designed to provide users with a seamless and efficient way to book movie tickets online. The application allows users to browse movies, view showtimes, select seats, and book tickets with ease.

## Features

- **Home Page:** Display current and upcoming movies.
- **Browse Movies:** View all available movies.
- **Seat Selection:** Select preferred seats from an interactive seat map.
- **Responsive Design:** Fully responsive and mobile-friendly interface.
- **User Authentication:** Secure login and registration for users.
- **Admin Panel:** Manage movies, showtimes, and bookings.

## Project Structure

The repository contains the following key files and directories:

- `index.php`: Main landing page of the application.
- `movies.php`: Page to browse all available movies.
- `book_seat.php`: Seat selection and booking page.
- `css/`: Directory containing CSS stylesheets.
- `js/`: Directory containing JavaScript files.
- `images/`: Directory containing image assets.

## Screenshots

### 1. Home Page
![home1](https://user-images.githubusercontent.com/104883953/167260990-670d3197-5c62-44bc-b821-fcc8d0efd36d.jpg)
![home2](https://user-images.githubusercontent.com/104883953/167261156-947f1206-6d2f-48c5-b3ba-319ff50b2e95.jpg)

### 2. All Movies
![all movie](https://user-images.githubusercontent.com/104883953/167261026-0c6d020e-7963-4e33-85e9-97b2b118d2e6.jpg)

### 3. Seat Booking
![seat book](https://user-images.githubusercontent.com/104883953/167261039-e45bb084-ed5a-4b43-b8d2-132a16100d41.jpg)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Ensure you have PHP and a web server (e.g., Apache) installed on your system.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/MovieTicketBookingSystem.git
    cd MovieTicketBookingSystem
    ```

2. Copy the project files to your web server's root directory (e.g., `htdocs` for XAMPP).

3. Import the database:
    - Create a database in your MySQL server.
    - Import the `database.sql` file provided in the repository.

4. Update the database configuration in `config.php` file with your database credentials.

## Usage

1. **Open the Application:**

    Open your web browser and navigate to `http://localhost/MovieTicketBookingSystem` to view the application.

2. **Browse and Book:**

    - Browse available movies on the home page.
    - Select a movie to view details and showtimes.
    - Choose your preferred showtime and seats, then proceed to book.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

Feel free to explore and contribute to the project. If you encounter any issues or have any questions, please open an issue or reach out. Happy coding!
