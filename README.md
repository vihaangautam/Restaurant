# Restaurant Management System

## Overview
The Restaurant Management System is a Java-based application designed to streamline restaurant operations. It offers functionalities for managing orders, items, and labor. The system provides a user-friendly graphical interface for efficient navigation and task handling.

## Features
- **Authentication System**: Secure login for authorized access.
- **Order Management**: Add, view, and manage customer orders.
- **Item Management**: Maintain an inventory of restaurant items.
- **Labor Management**: Manage restaurant staff details.
- **File Storage**: Data is stored locally in structured text files.

## Technologies Used
- **Programming Language**: Java
- **GUI Framework**: Swing
- **File Handling**: Java I/O

## Project Structure
### Packages
- **`restaurantsystem`**: Contains the main application entry point.
- **`restaurantsystem.component.auth`**: Handles the login functionality.

### Files
- **`Main.java`**: Entry point of the application.
- **`Login.java`**: Login page implementation.
- **Storage Files**:
  - `storage/item.txt`
  - `storage/labour.txt`
  - `storage/order.txt`
  - `storage/orderLine.txt`

### GUI Components
- **Panels**: Organized layouts for different functionalities.
- **Buttons**: Provide navigation and action triggers (e.g., "Order Management", "Item Management", "Exit").
- **Forms**: Built using NetBeans GUI Builder.


2. Open the project in NetBeans IDE.
3. Ensure the `storage` directory exists in the root folder.
4. Run the `Main.java` file to launch the application.

## Usage
1. **Login**:
   - Launch the application and log in using the authentication system.
2. **Navigate**:
   - Use the main menu to select the desired operation (Order, Item, or Labor Management).
3. **Exit**:
   - Click the "Exit" button to close the application.

## File Handling
- On startup, the application ensures required storage files (`item.txt`, `labour.txt`, `order.txt`, `orderLine.txt`) exist in the `storage` directory.
- If files are missing, they are automatically created.

## Future Enhancements
- Integration with a database for improved scalability.
- Enhanced reporting and analytics features.
- Role-based access control for added security.



