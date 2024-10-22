# Hati PHP Framework
A Slim 4-based PHP framework designed for simplicity, speed, and security. Hati provides a robust skeleton MVC application with built-in authentication, making development quick and efficient.

## ✨ Features

### ⚡ Lightweight and Organized
- Easy to Understand: Clean and organized code structure for efficient development.
- Simple and Fast Routing: Powered by the Slim 4 routing engine.

### 🔒 Secure and Ready-to-Use Authentication
- Authentication System: Secure user authentication with support for 2FA and WebAuthn.
- CSRF Protection: Ensure safety against cross-site request forgery attacks.
- Session Management: Optional Redis support for flexible session handling.

### 🔄 Flexible Database Access
- Integrated with PHP-DB: Convenient, safe, and driver-agnostic SQL database access.
- Safe Against SQL Injections: Prepared statements keep your queries secure.
- Native Data Types: Correctly typed data from the database for cleaner code.

### 📧 Built-In Email & SMS Communication
- Email Notification System: Send notifications directly from the framework.
- Customizable Email Templates: Easily modify templates to match your brand.
- SMS Integration: Support for SMS services for enhanced communication.

### 💳 Payment Integration
- Stripe and Adyen Payments: Seamlessly integrate with popular payment gateways.

### 🌐 Multi-Language Support
- Translation Ready: Easily localize your application for any language.

### 📊 Error Logging and Debugging
- Monolog Integration: Robust logging for easy troubleshooting and error reporting.
- Detailed HTML Error Reporting: Clear and concise error messages to help you debug.

### 🛠️ Developer-Friendly Utilities
- Helper Functions: Simplify development with built-in utility functions.
- PHP-CRUD-API: Quick and easy creation of RESTful APIs for your application.
- Twig Templating Engine: Flexible and powerful templates for crafting beautiful views.

## 🏁 Getting Started

### Prerequisites
Make sure you have the following installed:

- PHP 8.2+
- Composer
- Redis (optional, for session management)
- Supported databases: MySQL, PostgreSQL, SQLite, etc.

### Installation
1. Clone the repository:

```bash
git clone https://github.com/atriohq/hati
```

2. Navigate to the project directory:
```bash
cd hati
```

3. Install dependencies using Composer:
```bash
composer install
```

### Configuration
Copy the `.env.example` file to `.env` and set up your environment variables:

```bash
cp .env.example .env
```

Edit `.env` to configure your database, mail, and other settings.

### Running the Application

```bash
(tbd)
```

Open your browser and navigate to `http://localhost:8000` to see Hati in action.

## 📚 Documentation

Detailed documentation will be available here. Learn more about how to use Hati, including:

- Setting up routes
- Building controllers and models
- Using the authentication system
- Integrating payment services
- And more!

## 🎯 Contributing

Contributions are welcome! Please read our contribution guidelines before making a pull request.

## 🛡️ License

Hati is open-source software licensed under the MIT License.
