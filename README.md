# Salon Appointment Scheduler 💇‍♀️
This project involves the creation and management of a PostgreSQL database designed to handle salon appointments and customer interactions at a fictional salon. The application supports key functionalities such as booking services, managing customer records, and scheduling appointments.

## Features
- **View Available Services**: Customers can view the list of salon services offered, including cuts, colors, perms, styles, and trims.
- **Book an Appointment**: Customers can select a service and book an appointment by providing their phone number and preferred time.
- **New Customer Registration**: If a customer does not exist in the database, they can easily register by providing their name and phone number.
- **User-friendly Interface**: Provides clear instructions and prompts for customers to interact with the salon seamlessly.

## Project Structure
- `salon.sh` - The main Bash script that controls the appointment scheduling process and interacts with the PostgreSQL database.
- `salon.sql` - The SQL dump file to set up the salon PostgreSQL database with tables for services, customers, and appointments.

## Key Learnings

### Database Design
- **Structuring Tables for Business Logic**: Developed tables for services, customers, and appointments, structured to support efficient data retrieval and interaction. The design includes foreign keys and constraints to ensure data integrity across the salon's operations.

### SQL Queries
- **Using SQL for Business Operations**: Enhanced SQL skills by executing various queries essential for managing appointments, such as verifying customer information, inserting new records, and retrieving service details. Proficiently applied SELECT statements to extract relevant data for appointment scheduling.

### Data Manipulation
- **Data Integrity and Accuracy**: Practiced data manipulation techniques, including inserting, updating, and deleting records while ensuring data accuracy. Implemented validation checks to maintain consistency within tables.

### Error Handling
- **SQL and Bash Scripting Debugging**: Gained experience in identifying and resolving SQL syntax errors, unexpected values, and logical errors in Bash scripts. Developed a keen attention to detail for troubleshooting both SQL statements and Bash logic.

### Bash Scripting
- **Automation of Customer Interaction and Appointment Process**: Created Bash scripts that automate the main appointment operations, facilitating easier customer interactions and appointment management.
