# challenge13-E-commerce-Backend

## Description

A robust backend system for an e-commerce website built using Express.js API and Sequelize to interact with a MySQL database. This application provides a complete backend infrastructure that allows the company to compete with other e-commerce businesses by managing their products, categories, and tags.

## Features

- RESTful API endpoints for:
  - Categories (GET, POST, PUT, DELETE)
  - Products (GET, POST, PUT, DELETE)
  - Tags (GET, POST, PUT, DELETE)
- Database relationships and associations
- Data validation and error handling
- Sequelize ORM for database management

## Installation

1. Clone the repository:
   ```bash
   git clone git@github.com:JoseGuache/challenge13-E-commerce-Backend.git
   ```
2. Navigate to the project directory
3. Install dependencies:
   ```bash
   npm install
   ```
4. Create a `.env` file and add your PostgreSQL credentials:
   ```
   DB_NAME='ecommerce_db'
   DB_USER='your_username'
   DB_PASSWORD='your_password'
   DB_HOST='localhost'
   ```
5. Set up the database:
   ```bash
   psql -U postgres
   \i schema.sql
   ```

## Usage

1. Seed the database:
   ```bash
   npm run seed
   ```
2. Start the server:
   ```bash
   npm start
   ```
3. Use Insomnia or Postman to test the API endpoints:
   - Categories: `http://localhost:3001/api/categories`
   - Products: `http://localhost:3001/api/products`
   - Tags: `http://localhost:3001/api/tags`

## Technologies Used

- Node.js
- Express.js
- PostgreSQL
- Sequelize ORM
- dotenv for environment variables

## Repository

[View on GitHub](https://github.com/JoseGuache/challenge13-E-commerce-Backend)

## **Video:**

[Video](https://drive.google.com/file/d/18RWn-2xdC2psaRSm_hR254GSvs9v7FYc/view?usp=sharing)

## Credits

- Starter code provided by Professor Phil.
- [Professional README Guide](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) for details.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)