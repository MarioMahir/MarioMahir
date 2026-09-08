# Hi, I'm Mario Alejandro Sabala Encarnación 👋

**Software developer** focused on the .NET ecosystem: web applications, REST APIs, business systems and data pipelines with **C#**, **ASP.NET Core**, **Entity Framework Core** and **SQL Server**.

Software Development student at **ITLA (Instituto Tecnológico de las Américas)**, Santo Domingo. I like building complete systems end to end: clean architecture, real business rules, automated tests and documentation that lets anyone run the project.

---

## 🛠️ Tech Stack

| Area | Technologies |
|---|---|
| **Backend** | C#, ASP.NET Core MVC and Web API, Entity Framework Core (Code First), ASP.NET Core Identity, JWT, SignalR, MediatR (CQRS), FluentValidation, AutoMapper, Serilog, Azure Functions, Worker Services |
| **Data** | SQL Server, ADO.NET, star-schema data warehouses, ETL processes |
| **Frontend** | HTML, CSS, JavaScript, Bootstrap, Chart.js, Razor Views |
| **Testing** | xUnit, Moq, SQLite in-memory and EF Core InMemory |
| **Automation and analysis** | Python, Pandas, scikit-learn, n8n |
| **Tools** | Git, GitHub, Visual Studio, VS Code, Postman, Swagger, Docker |

---

## 📌 Featured Projects

### 🏦 [Artemis Banking Pro](https://github.com/MarioMahir/ArtemisBankingPro)

Banking platform built with **Onion Architecture and CQRS (MediatR)**. An **MVC WebApp** for administrators, tellers and clients (users, loans with amortization tables, credit cards, savings accounts, beneficiaries, transfers and payments with confirmation and e-mail), a **REST WebAPI** with JWT for administrators and merchants (including the *Hermes Pay* payment processor), an **Azure Function** that marks overdue installments, and **339 unit and integration tests**.

**Tech:** ASP.NET Core 9, Identity, JWT, EF Core, MediatR, FluentValidation, AutoMapper, Serilog, MailKit, Azure Functions, xUnit, Moq

<a href="https://github.com/MarioMahir/ArtemisBankingPro"><img src="https://raw.githubusercontent.com/MarioMahir/ArtemisBankingPro/main/docs/admin-home-datos.png" alt="Artemis Banking Pro" width="720"></a>

---

### 🏠 [RealEstateApp](https://github.com/MarioMahir/RealEstateApp)

Real estate platform with an **MVC WebApp** for clients, agents and administrators (property listings with filters and favorites, property management with images and improvements, agent and admin dashboards) and a **JWT-protected WebAPI** for administrators and developers, documented with Swagger. Both share the same database and Identity users.

**Tech:** ASP.NET Core 9, Onion Architecture, Identity, JWT, EF Core, AutoMapper, Swagger

<a href="https://github.com/MarioMahir/RealEstateApp"><img src="https://raw.githubusercontent.com/MarioMahir/RealEstateApp/main/docs/home-publico.png" alt="RealEstateApp" width="720"></a>

---

### 🗳️ [eVote360 Pro](https://github.com/MarioMahir/eVote360-Pro)

Electronic voting system covering the full electoral cycle: election setup by the administrator, candidates and political alliances managed by party leaders, and citizen voting with **ID card validation through OCR (Tesseract)** and a verification code sent by e-mail. Results per position once the election closes.

**Tech:** ASP.NET Core 9 MVC, Onion Architecture, Identity, EF Core, Tesseract OCR, MailKit

<a href="https://github.com/MarioMahir/eVote360-Pro"><img src="https://raw.githubusercontent.com/MarioMahir/eVote360-Pro/main/docs/resultados.png" alt="eVote360 Pro" width="720"></a>

---

### 📦 [ImportCost Pro](https://github.com/MarioMahir/ImportCostPro)

Import cost management for an importing company. Master data (countries, currencies, importers, suppliers, products, tariff categories, exchange rates), import orders with products and expenses, and a **landed cost engine**: currency conversion with the rate in force, expense allocation by FOB value, weight, volume or quantity, CIF, tariff, selective tax, customs service fee, ITBIS, unit cost and suggested selling price. The official calculation is stored with every value used, and orders are locked once calculated and closed.

**Tech:** ASP.NET Core 9 MVC, EF Core, SQL Server, Bootstrap

<a href="https://github.com/MarioMahir/ImportCostPro"><img src="https://raw.githubusercontent.com/MarioMahir/ImportCostPro/main/docs/landedcost-oficial.png" alt="ImportCost Pro" width="720"></a>

---

### 📊 [Sistema de Análisis de Opiniones](https://github.com/MarioMahir/SistemaAnalisisOpiniones)

**ETL process as a .NET 8 Worker Service** that extracts customer opinions from three sources in parallel (CSV files, a SQL Server database and a REST API), validates and loads a staging area, classifies sentiment with a keyword-based classifier, and populates a **star-schema data warehouse**. Includes KPI queries and a **dashboard in ASP.NET Core + Chart.js** with satisfaction trends by product, channel and month.

**Tech:** .NET 8 Worker Service, ADO.NET, CsvHelper, SQL Server, ASP.NET Core Minimal API, Chart.js, xUnit

<a href="https://github.com/MarioMahir/SistemaAnalisisOpiniones"><img src="https://raw.githubusercontent.com/MarioMahir/SistemaAnalisisOpiniones/main/docs/capturas/dashboard-completo.png" alt="Sistema de Análisis de Opiniones" width="720"></a>

---

### ✅ [TaskAPI](https://github.com/MarioMahir/TaskAPI)

Task management REST API with **JWT authentication**, **real-time notifications through SignalR** and a **reactive processing queue** built with System.Reactive. Documented with Swagger and covered by xUnit tests.

**Tech:** ASP.NET Core 8 Web API, JWT, SignalR, System.Reactive, EF Core, xUnit

---

## 🎯 Current Goals

* Earn Microsoft Azure certifications
* Keep building complete, production-oriented software
* Grow in backend architecture, cloud and data engineering

---

## 📫 Let's Connect

* 💼 LinkedIn: [mario-alejandro-sabala-encarnación](https://www.linkedin.com/in/mario-alejandro-sabala-encarnaci%C3%B3n-503324324)
* 💻 GitHub: [MarioMahir](https://github.com/MarioMahir)
