# Moco Project Readme

## Introduction
Moco is an innovative digital platform developed to address the literacy challenges in Indonesia by leveraging digital solutions. This project aims to enhance both traditional and digital literacy, creating a more educated and empowered generation ready to face global challenges.
![Platform Moco](https://example.com/path/to/image.jpg)
## Key Features

### 1. Focus Study
The Focus Study feature offers tools to improve personal literacy development. It includes a reading timer and a journaling feature where users can reflect on and record their reading experiences. This not only enhances understanding but also encourages a deeper engagement with the reading material, bridging the gap between digital content consumption and critical analysis.

### 2. Book Store
The Book Store feature simplifies the process of accessing physical and digital books. It addresses issues of affordability and availability of reading materials, ensuring that users from all economic backgrounds can access the necessary resources for education and self-learning.

### 3. Community
The Community feature enables users to engage with others' reading choices, participate in book discussion forums, and conduct discussions via audio. This fosters a supportive learning environment where users can share insights, enhance their social literacy skills, and contribute to a culture of reading.

## Development
The Moco website is developed using Laravel, a robust framework for web application development. Laravel facilitates efficient handling of routing, sessions, and authentication, which are integral for a dynamic website like Moco.

### Running the Project
To run the Moco project locally, follow these steps:

1. **Environment Setup:**
   - Ensure PHP and Composer are installed on your system.
   - Install Laravel by running `composer global require laravel/installer`.

2. **Clone the Repository:**
   - Use Git to clone the project repository to your local machine.

3. **Install Dependencies:**
   - Navigate to the project directory and run `composer install` to install the required PHP dependencies.

4. **Environment Configuration:**
   - Copy the `.env.example` file to `.env` and update the database and any other environment variables accordingly.

5. **Generate Key:**
   - Run `php artisan key:generate` to generate a unique key for your application.

6. **Run Migrations:**
   - Execute `php artisan migrate` to set up your database schema.

7. **Start the Server:**
   - Use `php artisan serve` to start the local development server. By default, this will host the application at `http://localhost:8000`.

8. **Access the Application:**
   - Open a web browser and navigate to `http://localhost:8000` to view and interact with the Moco platform.

The development of Moco is geared towards creating a comprehensive solution to literacy challenges in Indonesia, providing an accessible platform that integrates the benefits of digital innovation with the foundational aspects of educational development.


