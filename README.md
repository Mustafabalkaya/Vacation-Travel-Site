# Vacation_Travel_Site

This project is a web application developed using ASP.NET MVC, HTML, CSS, and JavaScript, focusing on the theme of travel and vacations. The system utilizes Microsoft SQL Server as the database, and migrations have been implemented for seamless database management.

## Features

1. **Room Rental:** Users can explore and rent vacation rooms. Room details, availability, and prices are dynamically retrieved from the MSSQL database.

2. **Car Rental:** The system provides a feature for users to rent vehicles for their travel needs. Car options, availability, and rental rates are managed in the MSSQL database.

3. **Hotel Reservations:** Users can browse and make reservations at various hotels. Hotel information, room availability, and reservation details are stored and retrieved from the MSSQL database.

4. **Migration:** Database migration is implemented for easy and efficient database management. This ensures that the database schema stays updated with the latest changes in the application.

## Technologies Used

- ASP.NET MVC
- HTML
- CSS
- JavaScript
- BootStrap
- MSSQL (Database with Migration)

## Database Migration

1. Open the Package Manager Console in Visual Studio.
2. Run the following command to add a new migration:
   ```
   Add-Migration InitialCreate
   ```
3. After making changes to the model, update the database using the following command:
   ```
   Update-Database
   ```

## Installation

1. Clone the repository to your local machine.
2. Open the project using Visual Studio or a similar IDE.
3. Ensure that MSSQL Server is installed on your machine.
4. Run the database migration commands mentioned above to set up the database.
5. Run the project.



