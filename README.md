# SOC Ticket Booking Website

![Homepage](ss/homepage.JPG)

Welcome to the SOC Ticket Booking Website repository, a sophisticated ticket booking system developed using Service Oriented Computing (SOC) principles. This project harnesses the power of ASP.NET and C# to build robust services and classes, ensuring a modular and scalable architecture. The services in this project include GET, POST, PUT, and DELETE methods.

## Getting Started

### Downloading the Project

Download the project from the [Google Drive](https://drive.google.com/drive/folders/1gNigWdldwPy_pDovC5Kin5Ks9ADBDOxA?usp=sharing) or use the link provided in the text file.

### Setting up the Project

1. **Open the Project**: Launch Microsoft Visual Studio and open the project file.
2. **Database Configuration**: Before running the project, ensure correct SQL connection.
   - Open SQL Management Studio, copy the server name from the Connect to Object Explorer window.
   - In Microsoft Visual Studio, go to Tools -> Connect to Database, paste the server name, select the database name ("Debra"), and click OK.

### Database Configuration

- **Server Name**: THEVINDU\SQLEXPRESS02 (Replace with your server name)
- **Database Name**: Debra

### Testing API Methods

During development, [Postman](https://www.postman.com/) was used to test the API methods (GET, POST, PUT, DELETE).

### Development Tools

- [Microsoft Visual Studio](https://visualstudio.microsoft.com/)
- [SQL Management Studio](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)
- [Postman](https://www.postman.com/)

## Note

If another person is running this project, replace the server name in the controllers with their server name, replacing "THEVINDU\SQLEXPRESS02". The database name should remain "Debra".

## License

This project is licensed under the MIT License. For details, see the [LICENSE](LICENSE) file.
