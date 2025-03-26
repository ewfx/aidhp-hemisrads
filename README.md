# 🚀 Project Name

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction
A brief overview of your project and its purpose. Mention which problem statement are your attempting to solve. Keep it concise and engaging.

## 💡 Inspiration
What inspired you to create this project? Describe the problem you're solving.

## ⚙️ What It Does
Explain the key features and functionalities of your project.

## 🛠️ How We Built It
We have used EF Core code first approach here.
We used dot net core with sql sever - entity framework. 

## 🚧 Challenges We Faced
Binding recommendations

## 🏃 How to Run
1. Clone the repository  
   ```sh
   git clone https://github.com/ewfx/aidhp-hemisrads.git
   ```
2. Pre-requisites
   ```sh
   Dot Net Core 3.1(.Net framework) and Sql Server
   ```
2. Setup
   ```sh
 Steps to create the database and tables:
1) Go to SqlServer Management Studio.Connect to local DB ( using . or localhost)
2) Create a database with name "test_ECommerceDB"
3) Go to Visual Studio Menu >> Tools >> NuGet Package Manager >> Package Manager Console and run below commands:
 Update-Database -Context ECommerceDbContext

 Database will be created with tables and data will be inserted in the tables.
   ```
3. Run the project  
   ```sh
    1) Open the solution "HemisRadsShoppingCart.sln" in Visual 
 2) Right click on the solution and click on "Restore NuGet Packages"
 3) Right click on the solution and click on "Build Solution"
 4) Right click on the project "HemisRadsShoppingCart" and click on "Set as StartUp Project"
 5) Press F5 to run the application

or
in command prompt(go the downloaded path where solution file exists), use below command

dotnet run
```

## 🏗️ Tech Stack
- 🔹 Frontend: HTML, Jquery
- 🔹 Backend: Dotnet Core MVC
- 🔹 Database: SqlServer, EntityFramework
- 🔹 Other: Microsoft.Extensions.AI
  
## 👥 Team
- **HEMIS-RADS**
- Team Members:
  Ranjith Kumar P
  Vellanki Sai
  Dibyajyoti Dev
  Avinash Shivaram K
