# Hahn Software (Application Process)

The presented system is a simple employee control for the human resources sector, containing employee information such as: name, salary, department, etc.
It uses an API with the methods: Get, Put, Update and Delete, interacting with a screen containing fields to be filled in.
The purpose of this project is to be able to demonstrate my skills in software development.
In a short period, approximately 8 days, I needed to learn how to basically use the syntax of the C# language and its famous .NET framework and, I confess that it has not been easy, but I believe it was a good experience, since being used to and studying Java and Spring Boot for more than 1 year, this change made me revise a lot to be able to use it.
I also needed to study more about Docker to create an image of the project, making it available and functional to be accessed remotely, without the need to configure the computer.
Regarding the Angular part, I had already used it in another project and I liked the logical practicality, in addition to the formatting in HTML, CSS, JavaScript and Typescript not being much of a personal preference, but I faced the challenge and I hope it turned out to be interesting, despite all simplicity.
I thank God for this opportunity and trust Him with my life.
## Technologies used

> - [Angular](https://angular.io/)
> - [C#](https://docs.microsoft.com/pt-br/dotnet/csharp/)
> - [Docker](https://www.docker.com/)
> - [Entity Framework](https://docs.microsoft.com/pt-br/ef/)
> - [SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads)
> - [Swagger](https://swagger.io/)
> - [Visual Studio Code](https://code.visualstudio.com/)
> - [Visual Studio](https://visualstudio.microsoft.com/pt-br/)
> - [Bootstrap](https://getbootstrap.com/)

## How to run

> - Clone the project
> - Open the project in Visual Studio Code
> - Open the terminal and run the command `dotnet run`
> - Open the browser and access the address `http://localhost:(port-number)/swagger/index.html`
> - Open the project in Visual Studio
> - Run the project
> - Open the terminal and run the command `docker-compose up`

## How to use

> - Access the address `http://localhost:(port-number))/swagger/index.html`
> - Click on the `Employee` button
> - Click on the `Get` button
> - Click on the `Try it out` button
> - Click on the `Execute` button
> - Click on the `Put` button
> - Click on the `Try it out` button
> - Click on the `Execute` button
> - Click on the `Post` button
> - Click on the `Try it out` button
> - Click on the `Execute` button
> - Click on the `Delete` button
> - Click on the `Try it out` button
> - Click on the `Execute` button


## CrudApi
This project was generated with [DotNet CLI](https://learn.microsoft.com/pt-br/dotnet/core/tools/) version 6.0.113.

## Development server
Run `dotnet run` for a dev server. Navigate to the generated `http://localhost:portnumber/`. The application will automatically reload if you change any of the source files.
    
## ConnectionString
You need to change your ConnectionString based on your <strong>Server Name</strong>. In my case I used a Docker Container with SqlServer 2022 on it, and accessed on DBeaver to use it GUI.
    
## DotNet Packages
The packages used in the project are located in `/CrudApi/CrudApi.csproj`. If doesn't load, you just need to remove in the CrudApi.csproj and reinstall it by the DotNet CLI
