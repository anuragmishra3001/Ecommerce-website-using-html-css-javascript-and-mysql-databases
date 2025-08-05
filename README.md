# Online Shopping System

A complete PHP-based online shopping system with user authentication, product management, shopping cart, and payment integration.

## Features

- **User Authentication**: Customer registration and login system
- **Product Management**: Browse products, view details, and search functionality
- **Shopping Cart**: Add/remove items, update quantities
- **Checkout System**: Secure checkout process with payment integration
- **Admin Panel**: Product and order management for administrators
- **Payment Integration**: PayPal payment gateway support
- **Responsive Design**: Modern UI with CSS styling

## Technology Stack

- **Backend**: PHP
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript
- **Payment**: PayPal Integration
- **Server**: Apache (XAMPP)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/online-shopping-system.git
   cd online-shopping-system
   ```

2. **Set up the database**
   - Import the `database/ecom.sql` file into your MySQL database
   - Update database connection settings in `database/connection.php`

3. **Configure the server**
   - Place the project in your web server directory (e.g., `htdocs` for XAMPP)
   - Ensure PHP and MySQL are properly configured

4. **Set up environment variables**
   - Create a `.env` file with your database credentials
   - Configure PayPal API credentials if using payment features

## Project Structure

```
online_shopping-master/
├── admin_area/          # Admin panel files
├── customer/            # Customer-specific files
├── database/            # Database schema and connection
├── functions/           # PHP helper functions
├── images/              # Product images and assets
├── includes/            # Common includes and headers
├── styles/              # CSS styling files
├── index.php            # Main entry point
├── cart.php             # Shopping cart functionality
├── checkout.php         # Checkout process
├── payment.php          # Payment processing
└── README.md            # Project documentation
```

## Usage

1. **For Customers**:
   - Register/Login to your account
   - Browse products and add them to cart
   - Complete checkout and payment process

2. **For Administrators**:
   - Access admin panel at `/admin_area/`
   - Manage products, orders, and customer data

## Deployment

This project can be deployed on various platforms:

- **Vercel**: Configure as a PHP project
- **Heroku**: Use PHP buildpack
- **Traditional Hosting**: Upload to any PHP-compatible hosting service

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For support and questions, please open an issue on GitHub or contact the development team. 