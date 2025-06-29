# E-Commerce Store

A customizable PHP-based e-commerce platform for building and managing online stores. This repository provides a foundation for selling products, managing customers, processing payments, and more.

# Hosted on:
https://babasouk.store/

## Features

- **User Authentication & Profile Management**
  - Registration, login, logout, and password reset
  - Customer billing and shipping address management
  - Profile updates

- **Product Catalog**
  - Product listing, search, and categorization
  - Product detail view

- **Shopping Cart & Checkout**
  - Add, update, and remove items from the cart
  - Secure checkout process
  - Order placement and review

- **Order Management**
  - Customer order history and details
  - Admin dashboard for order tracking

- **Payment Integration**
  - Payment processing and post-payment success handling

- **Admin Panel**
  - Manage products, categories, customers, and orders

- **Contact & FAQ**
  - Customer contact form
  - Frequently asked questions section

- **Security**
  - User session handling
  - Password management

## Project Structure

- `/admin` - Administrative backend for managing the store
- `/assets` - Static assets (images, CSS, JS)
- `/payment` - Payment processing modules
- `DATABASE FILE/` - Database schema and data dumps
- Key PHP scripts for core features (e.g., `cart.php`, `checkout.php`, `product.php`, `customer-profile-update.php`)

> **Note:** This list is based on a partial directory listing. For the full project structure, visit the [repository file browser](https://github.com/jaltiyassine/e-commerce-store/tree/main).

## Getting Started

1. **Clone the Repository**

   ```bash
   git clone https://github.com/jaltiyassine/e-commerce-store.git
   cd e-commerce-store
   ```

2. **Set Up the Database**

   - Import the schema from the `DATABASE FILE` directory using your preferred database tool (e.g., phpMyAdmin or MySQL CLI).

3. **Configure Environment**

   - Update database connection settings in your PHP configuration files.

4. **Run Locally**

   - Deploy files to your local web server (e.g., XAMPP, WAMP, LAMP).
   - Access the website via `http://localhost/e-commerce-store`.

## Requirements

- PHP 7.4 or higher
- MySQL or MariaDB
- Web server (Apache/Nginx recommended)

## Customization

- Update styles and assets in the `/assets` directory.
- Modify or extend PHP scripts for additional features.
- Customize the admin dashboard in `/admin`.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is open-source. See [LICENSE](LICENSE) for details.

## Contact

For questions or support, use the contact form on the site or open an issue.