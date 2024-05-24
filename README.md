

# BilSup.com

Welcome to BilSup.com! This project is a comprehensive platform that allows customers to view discounted products, register for accounts, edit profiles, and manage their purchases. Market users can register, add, delete, and edit products to keep the product listings up-to-date.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Photos](#project-photos)
- [Contributions](#contributions)
- [Contributing](#contributing)


## Features

### Customer Features
- **View Discounted Products**: Browse through a list of products that are currently on discount.
- **Expired Products**: Identify and manage expired products.
- **Customer Registration**: Create a new customer account.
- **Profile Editing**: Update personal information and password.
- **View Purchase History**: Track past purchases and view details.

### Market User Features
- **Market User Registration**: Create a new market user account.
- **Add Products**: List new products for customers to see.
- **Edit Products**: Modify product details such as price, description, and discount.
- **Delete Products**: Remove products that are no longer available.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/BilSup.com.git
   cd BilSup.com
   ```

2. **Install dependencies:**
   ```sh
   composer install
   ```

3. **Set up the database:**
   - Create a database named `test`.
   - Import the provided `market.sql` file into your database.

4. **Configure the environment:**
   - Copy `.env.example` to `.env` and update the environment variables accordingly.

5. **Run the application:**
   ```sh
   php -S localhost:8000
   ```

6. **Access the application:**
   - Open your web browser and go to `http://localhost:8000`.

## Usage

### Customer Registration
- Navigate to the registration page and fill in your details to create an account.
- Verify your email using the code sent to your email address.

### Market User Actions
- After registering as a market user, log in to access the product management dashboard.
- Use the dashboard to add new products, edit existing products, or delete products.

## Project Photos

### Home Page
![Screenshot 2024-05-24 224026](https://github.com/EmirCtis0/BilSup.com/assets/145711137/9b6eefa0-28df-4a0e-b8c6-22a58b6a92e6)


### Customer Registration
![Screenshot 2024-05-24 224058](https://github.com/EmirCtis0/BilSup.com/assets/145711137/ade0935d-02ba-47d9-bad9-fdf0d9fbd3bc)

### Customer Login
![Screenshot 2024-05-24 224043](https://github.com/EmirCtis0/BilSup.com/assets/145711137/8e38afbf-9059-4b9f-864a-8831121e8d29)

### Customer Edit
![Screenshot 2024-05-24 224329](https://github.com/EmirCtis0/BilSup.com/assets/145711137/c5f92261-2952-4047-8024-e605e548ba99)

### Product Listing
![Screenshot 2024-05-24 224230](https://github.com/EmirCtis0/BilSup.com/assets/145711137/ad402013-90b1-4a50-93ca-f1e2349758d4)

### Shoping Cart
![Screenshot 2024-05-24 224939](https://github.com/EmirCtis0/BilSup.com/assets/145711137/a6ef4e61-b6d3-4093-bc8b-9dc2b81f6658)

### Market User Dashboard
![Screenshot 2024-05-24 224358](https://github.com/EmirCtis0/BilSup.com/assets/145711137/85404952-8453-4611-9dee-12649c399565)

### Product Editing
![Screenshot 2024-05-24 224419](https://github.com/EmirCtis0/BilSup.com/assets/145711137/9a0c1d71-4a8d-4074-84ba-e5f00caa31f4)


## Contributions

This is a team project developed collaboratively. Below are my specific contributions:

### [Emir inaner]
- **UX/UI Design**: Designed the user interface for both customer and market user sections.
- **Validation & Sanitization**: Implemented validation and sanitization logic for user input to ensure data integrity and security.
- **Product Management**: Developed features for adding and editing products in the market user dashboard.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your improvements.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.


