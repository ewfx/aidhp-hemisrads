# 🚀 AI-Driven Hyper Personalization & Recommendations 

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
Welcome to the world of AI-driven hyper-personalization, where technology meets individuality. In today's digital landscape, users expect experiences tailored to their unique preferences and interests. AI-driven hyper-personalization makes this possible, using machine learning algorithms to analyze user behavior and provide relevant, real-time recommendations. From content and product suggestions to customer service and health advice, the applications of AI-driven hyper-personalization are vast and growing. Let's explore the possibilities and potential of this exciting technology.

## 💡 Inspiration
Here are some inspirational ideas:

People
1. *Elon Musk*: A pioneer in AI and technology, inspiring innovation and pushing boundaries.
2. *Andrew Ng*: A leading AI expert, advocating for AI's potential to improve lives.
3. *Fei-Fei Li*: A renowned AI researcher, driving AI advancements and promoting diversity.

Quotes
1. *"AI is the new electricity."* - Andrew Ng
2. *"The future of AI is not about replacing humans, but augmenting them."* - Fei-Fei Li
3. *"The best way to predict the future is to invent it."* - Alan Kay

Books
1. *"Life 3.0: Being Human in the Age of Artificial Intelligence"* by Max Tegmark
2. *"Deep Learning"* by Ian Goodfellow, Yoshua Bengio, and Aaron Courville
3. *"The Singularity Is Near"* by Ray Kurzweil

TED Talks
1. *"The future of learning"* by Fei-Fei Li
2. *"How AI is changing the world"* by Andrew Ng
3. *"The thrilling potential of Sixth-Grade Science"* by Cynthia Breazeal

Podcasts
1. *The AI Alignment Podcast*
2. *The Data Science Podcast*
3. *The AI in Industry Podcast*

## ⚙️ What It Does
Provides recommendations for shopping on site cart on basis of social activities, sentiments, search, user information

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
3. Setup

 Steps to create the database and tables:
a. Go to SqlServer Management Studio.Connect to local DB ( using . or localhost)
b. Create a database with name "test_ECommerceDB"
c. Go to Visual Studio Menu >> Tools >> NuGet Package Manager >> Package Manager Console and run below commands:
 Update-Database -Context ECommerceDbContext

 Database will be created with tables and data will be inserted in the tables.
   
4. Run the project  
   
a. Open the solution "HemisRadsShoppingCart.sln" in Visual

b. Right click on the solution and click on "Restore NuGet Packages"

c. Right click on the solution and click on "Build Solution"

d. Right click on the project "HemisRadsShoppingCart" and click on "Set as StartUp Project"

e. Press F5 to run the application

(or) 

in command prompt(go the downloaded path where solution file exists), use below command

```sh
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
