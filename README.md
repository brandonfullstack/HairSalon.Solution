# _Eau Claire's Hair Salon_

#### By _**Brandon Wright**_

#### _A simple employee/client management web app_

## Technologies Used

* _C#_
* _.NET_
* _ASP.NET Core_ 
* _MVC_
* _Razor_
* _HTML_
* _CSS_
* _Git_

## Description

_An awesome web application for managing employees and clients of Eau Claire's Hair Salon._

## Setup/Installation Requirements

Note: An installation of the .NET SDK is required in order to run this application locally. See [Here](https://dotnet.microsoft.com/en-us/) for installation.

1. Copy project directory or clone repo from Github (https://github.com/brandonfullstack/HairSalon.Solution) to your desktop.
2. Open your terminal (e.g., Terminal or GitBash) and navigate to this project's production directory called "HairSalon".
3. Create a file named `appsettings.json`: `$ touch appsettings.json`
4. Within `appsettings.json` add the following code, replacing the uid and pwd values with your own username and password for MySQL.

    ```json
    {
      "ConnectionStrings": {
          "DefaultConnection": "Server=localhost;Port=3306;database=ryans_todo_from_section3;uid=[YOUR-USERNAME];pwd=[YOUR-MYSQL-PASSWORD];"
      }
    }
    ```

5. Set up the Database. Follow the instructions in the LearnHowToProgram.com lesson ["Creating a Test Database: Exporting and Importing Databases with MySQL Workbench"](https://www.learnhowtoprogram.com/c-and-net/database-basics/creating-a-test-database-exporting-and-importing-databases-with-mysql-workbench) to use the `brandon_wright.sql` file located at the top level of this repo to create a new database in MySQL Workbench with the name `brandon_wright`.
6. Navigate to the project directory: `$ cd HairSalon`
7. In the command line, run the command "dotnet watch run" to compile and execute the web application. Since this is a web application, you'll interact with it through the UI in your browser.
8. Open the browser at: https://localhost:5001. If you cannot access localhost:5001 it is likely because you have not configured a .NET developer security certificate for HTTPS. To learn about this, review this lesson: [Redirecting to HTTPS and Issuing a Security Certificate](https://www.learnhowtoprogram.com/c-and-net/basic-web-applications/redirecting-to-https-and-issuing-a-security-certificate).

## Known Bugs

* _No known issues_
* _Please visit this projects [GitHub repository](https://github.com/brandonfullstack/HairSalon.Solution) to submit Issues and Pull Requests._

## License

_[MIT](https://choosealicense.com/licenses/mit/)_

Copyright (c) _2023_ _Brandon Wright_