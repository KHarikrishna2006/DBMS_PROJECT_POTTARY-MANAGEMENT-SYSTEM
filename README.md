# Pottery Management System

## Overview 

The **Pottery Management System** is a comprehensive Database Management System (DBMS) project designed to efficiently manage and organize pottery business operations. This system streamlines the management of products, customers, orders, inventory, and transactions in a pottery enterprise.

## Key Features

- **Product Management** - Manage pottery items, designs, and specifications
- **Customer Management** - Track customer information and purchase history
- **Order Processing** - Handle order creation, tracking, and fulfillment
- **Inventory Control** - Monitor stock levels and material availability
- **Transaction Management** - Record and manage all business transactions
- **Database Design** - Well-structured relational database with Entity-Relationship diagrams

## Project Structure

```
DBMS_PROJECT_POTTERY-MANAGEMENT-SYSTEM/
|-- DBMS_ER.drawio
|-- DBMS_ER.drawio.pdf
|-- DBMS_ER.drawio1.pdf
|-- ER-Image.jpg
|-- Tables.drawio
|-- Tables.drawio.pdf
|-- Pottery_Management_Entities_and_Relationships.docx
`-- Pottery_management_Queries.docx
```

## Core Database Entities

1. **Products** - Pottery items with name, type, price, specifications
2. **Customers** - Customer information with contact details
3. **Orders** - Order details linking customers to products
4. **Inventory** - Stock management for materials and finished products
5. **Transactions** - Financial records of business operations
6. **Employees** - Staff information and roles

## File Descriptions

### Database Diagrams
- **DBMS_ER.drawio** - Editable Entity-Relationship diagram
- **DBMS_ER.drawio.pdf / DBMS_ER.drawio1.pdf** - PDF versions of ER diagrams
- **ER-Image.jpg** - Quick reference image of ER diagram
- **Tables.drawio** - Detailed database table structure diagram
- **Tables.drawio.pdf** - PDF version of table structure

### Documentation Files
- **Pottery_Management_Entities_and_Relationships.docx** - Entity specifications and relationships
- **Pottery_management_Queries.docx** - Sample SQL queries for operations

## Getting Started

### Prerequisites
- Database Management System (MySQL, PostgreSQL, SQL Server)
- Diagram viewer (Draw.io)
- SQL client or IDE

### Setup Instructions

1. **Review Database Design**
   - Open DBMS_ER.drawio or ER-Image.jpg to understand the structure
   - Examine Tables.drawio for table specifications

2. **Create Database**
   - Refer to Pottery_Management_Entities_and_Relationships.docx for entity details
   - Use Pottery_management_Queries.docx for SQL scripts

3. **Implement Database**
   - Execute SQL scripts to create tables
   - Set up primary keys, foreign keys, and indexes

4. **Test Operations**
   - Run provided queries for data operations
   - Verify data integrity and relationships

## Database Relationships

- **One-to-Many**: Customers to Orders, Products to Inventory
- **Many-to-Many**: Orders to Products (via order details)
- **Referential Integrity**: Foreign key constraints ensure consistency

## Use Cases

1. **Order Processing** - Create and track orders
2. **Inventory Management** - Monitor stock and reordering
3. **Customer Analytics** - Analyze purchase patterns
4. **Financial Reporting** - Generate transaction reports
5. **Product Catalog** - Manage pottery products

## Technologies Used

- **Database**: Relational Database Systems
- **Modeling**: Draw.io
- **Documentation**: Microsoft Word
- **Language**: SQL

## Key Features

- Normalization principles for data consistency
- Referential integrity maintenance
- Scalable design for growing businesses
- Sample queries for common operations

## Author

**KHarikrishna2006**

## License

This project is provided for educational and business purposes.

## Contributing

Feel free to contribute improvements and suggestions.

---

**Last Updated**: January 2026
