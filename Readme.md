# Local Business Marketplace with JsonPowerDB

## Table of Contents
- [Description](#description)
- [Benefits of JsonPowerDB](#benefits-of-jsonpowerdb)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Status](#project-status)
- [Release History](#release-history)

## Description
A hyperlocal platform enabling small businesses to manage and list their products using JsonPowerDB. This web application provides a simple, efficient way to perform CRUD (Create, Read, Update, Delete) operations on product inventories.

## Benefits of JsonPowerDB
- High-performance NoSQL database
- Schema-free JSON data storage
- Real-time data synchronization
- Low memory and processing requirements
- Simple PUT, GET, UPDATE, and DELETE commands
- Multi-mode database support

## Features
- Add new products
- Update existing products
- Delete products
- View product listings
- Real-time data management
- Category-based product organization

## Installation
1. Clone the repository
2. Replace connection token in the script
3. Open `index.html` in a web browser

### Prerequisites
- Modern web browser
- Internet connection
- JsonPowerDB connection token

## Usage
```javascript
// Sample product addition
{
    "token": "YOUR_CONNECTION_TOKEN",
    "cmd": "PUT",
    "dbName": "LOCAL_MARKETPLACE",
    "rel": "PRODUCTS",
    "jsonStr": {
        "id": "1",
        "businessName": "Local Store",
        "productName": "Organic Apples",
        "price": "5.99",
        "category": "Groceries",
        "description": "Fresh local organic apples"
    }
}
```

## Project Status
🟢 Active Development
- Core functionality implemented
- Open to contributions and improvements

## Release History
- v1.0.0 (2024-02-15): Initial release
  * Basic CRUD operations
  * JsonPowerDB integration
  * Responsive design

## Contributing
1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Create pull request

## License
MIT License