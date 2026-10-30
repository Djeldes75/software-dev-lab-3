# Software Development Lab 3

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%20Framework%204.8%20%7C%20.NET%2010-512BD4?style=flat&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![Course](https://img.shields.io/badge/INTEC-coursework-3E9A86?style=flat)

Lab projects from **Desarrollo de Software 3**: desktop apps with SQL Server, client–server communication
over TCP sockets and HTTP, web services, ASP.NET MVC, messaging with NServiceBus and SSRS reports.

## Projects

| Project | What it is | Tech |
|---|---|---|
| [`BakerySolution-DJ`](BakerySolution-DJ) | Bakery point of sale with users and roles | ASP.NET Core MVC (.NET 10), Entity Framework Core |
| [`LabNServiceBus`](LabNServiceBus) | Order flow split into services: client, sales, billing, shipping | NServiceBus, .NET 10 |
| [`SistemaVentas`](SistemaVentas) | Sales system with messaging between a client and a sales service | NServiceBus, .NET 10 |
| [`DenunciasSolution`](DenunciasSolution) | Complaints service and a client that calls it | ASP.NET Core web service + HTTP client |
| [`App_Pizarra`](App_Pizarra) | Baseball scoreboard: web service, client and console app | ASP.NET MVC, .NET Framework 4.8 |
| [`RegistroCliente`](RegistroCliente) | Customer registration with a client and a server | TCP sockets, SQL Server |
| [`DBReportes`](DBReportes) | Invoice report on the AdventureWorks database | SQL Server Reporting Services |
| [`ReclutarDominicanos`](ReclutarDominicanos) | Recruitment app with its database script | Console, SQL Server |
| [`App_ControlPresos`](App_ControlPresos) | Inmate control | Console, SQL Server |
| [`App_VentaTickets-Ilegal`](App_VentaTickets-Ilegal) | Ticket sales (concurrency exercise) | Console, threads, SQL Server |
| [`AppPara telenoticias`](AppPara%20telenoticias) | News broadcast app | Windows Forms, threads, SQL Server |
| [`SolucionEntregaCedula`](SolucionEntregaCedula) | ID card delivery | Windows Forms |
| [`SolucionFiestaNavidad`](SolucionFiestaNavidad) | INTEC Christmas party | Windows Forms |
| [`SolucionInscripcionAI`](SolucionInscripcionAI) | Course enrollment | Windows Forms |
| [`Semana1-Donativos`](Semana1-Donativos) | Donations (week 1) | Windows Forms |

`PizzaraBaseball`, `PizzaraCliente` and `PizzaraWebService` are the individual projects of `App_Pizarra`.

## How to run

1. Open the project's `.sln` (or `.slnx`) file in **Visual Studio 2022** or later.
2. Projects that use a database need **SQL Server** (LocalDB works); check the connection string in the code or in `appsettings.json`.
3. Press **F5**. Build folders (`bin`, `obj`) are created on build and are not stored in this repository.

## About

Coursework by **Dominique Jeldes** for the Systems Engineering program at
[INTEC](https://www.intec.edu.do/) (Instituto Tecnológico de Santo Domingo), Dominican Republic.
Educational code: some projects are exercises or work in progress.
