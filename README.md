# InventoryMaster - Stock Control System

**InventoryMaster** is a robust and user-friendly stock control system developed in **C#** with a **SQL Server** backend. It enables businesses to efficiently manage their inventory, track stock levels, and generate insightful reports.

---

## Features

- **Product Management**: Add, update, and delete products in the inventory.
- **Stock Level Tracking**: Monitor real-time stock levels to avoid overstocking or stockouts.
- **Sales and Purchase Records**: Maintain a detailed history of sales and purchases.
- **User Authentication**: Secure login system with role-based access.
- **Reporting**: Generate detailed reports on inventory, sales, and purchases.
- **Scalable Database**: Built on SQL Server to handle large datasets and complex queries.

---

## Technology Stack

- **Frontend**:  
  - **C# (WinForms)**: For creating an intuitive and responsive desktop application.  
- **Backend**:  
  - **SQL Server**: For data storage and management.  
- **Libraries and Frameworks**:  
  - ADO.NET for database interaction.  
  - Microsoft Visual Studio for development.  

---

## Installation

### Prerequisites

1. **Windows OS**: The application is built for Windows.
2. **SQL Server**: Ensure SQL Server is installed and running.
3. **.NET Framework**: Required to run the application (ensure compatibility with the .NET version used).

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Younes-Alaoui-Ismaili/InventoryMaster-Stock-Control-System-C-SQL-.git
   cd InventoryMaster-Stock-Control-System-C-SQL-
   ```

2. **Restore the Database**:
   - Locate the `InventoryMaster.sql` file in the repository.
   - Open SQL Server Management Studio (SSMS).
   - Restore the database using the provided `.sql` file.

3. **Configure the Connection String**:
   - Open the `App.config` file in the project.
   - Update the connection string with your SQL Server instance details:
     ```xml
     <connectionStrings>
       <add name="InventoryMasterDb" 
            connectionString="Server=<Your_Server_Name>;Database=InventoryMaster;User Id=<Your_Username>;Password=<Your_Password>;" 
            providerName="System.Data.SqlClient" />
     </connectionStrings>
     ```

4. **Run the Application**:
   - Open the project in **Microsoft Visual Studio**.
   - Build and run the application.

---

## Screenshots

### Dashboard
![Dashboard](https://user-images.githubusercontent.com/52432709/61491137-8ee63080-a97c-11e9-9c43-287bb23fe208.png)

### Product Management
(Add a screenshot here showing the product management feature if available. Example: `![Product Management](Product-Management.png)`)

---

## Future Enhancements

- **Multi-Language Support**: Expand the application's usability by adding support for multiple languages.
- **Barcode Integration**: Allow users to scan products for quick updates or searches.
- **Cloud Backup**: Implement cloud storage for data redundancy and remote access.

---

## Contribution

Contributions are welcome! If you'd like to improve this project, feel free to fork the repository, create a branch, and submit a pull request.

---

## License

This project is licensed under the **Younes Alaoui Ismaili** License. Unauthorized use, reproduction, or distribution is prohibited unless explicit permission is granted.
