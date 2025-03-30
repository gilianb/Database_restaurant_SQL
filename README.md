# Database Restaurant SQL

## Overview

This repository contains a **structured SQL database** designed for managing **restaurant operations**. It includes schemas, sample data, and queries to handle various aspects of restaurant management, such as **menu items, orders, customers, and staff**.

## Features

- **Comprehensive Schema**: Covers all essential entities like **Menu, Orders, Customers, and Staff**.
- **Sample Data**: Pre-populated data for testing and demonstration purposes.
- **Efficient Queries**: Includes common queries for **data retrieval and management**.
- **Scalable Design**: Easily extendable to accommodate additional features or entities.

## Technologies

- **Database**: SQL (Structured Query Language)
- **DBMS Compatibility**: MySQL, PostgreSQL, SQLite

## Installation

### Prerequisites

- A SQL-compatible database management system (e.g., MySQL, PostgreSQL, SQLite)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/gilianb/Database_restaurant_SQL.git
   cd Database_restaurant_SQL
   ```

2. Set up the database:
   - Open your SQL database client.
   - Execute the `schema.sql` file to create the database structure:
     ```sql
     source schema.sql;
     ```

3. Populate the database with sample data:
   - Execute the `data.sql` file:
     ```sql
     source data.sql;
     ```

## Usage

### Example Queries

- **Retrieve all menu items**:
  ```sql
  SELECT * FROM Menu;
  ```

- **Find orders by a specific customer**:
  ```sql
  SELECT * FROM Orders WHERE customer_id = 1;
  ```

- **Calculate total sales**:
  ```sql
  SELECT SUM(total_amount) FROM Orders;
  ```

## Contributing

We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push to your fork and submit a pull request.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, please contact:

- **Gilian B.**
- GitHub: [@gilianb](https://github.com/gilianb)

---

⭐ If you find this project useful, please consider giving it a star! ⭐

