# contosoPizza

# ContosoPizza API

ContosoPizza är ett ASP.NET Core Web API-projekt som simulerar en enkel pizzabutik. Syftet med projektet är att lära sig grunderna i att bygga RESTful API:er med ASP.NET Core, inklusive hur man skapar controllers, modeller och använder tjänster (services) för att hantera data.

## 🎯 Syfte

Syftet med detta projekt är att:

- Lära sig hur man bygger ett API med ASP.NET Core.
- Förstå hur man använder routing och HTTP-metoder (GET, PUT, DELETE).
- Arbeta med modeller och tjänstelager (services).
- Testa API:et med verktyg som Swagger och HTTP REPL.

## 🔧 Funktioner

- Hämta alla pizzor
- Hämta en pizza med ett ID
- Uppdatera en pizza
- Ta bort en pizza

## 📁 Projektstruktur

ContosoPizza/
├── Controllers/
│ └── PizzaController.cs
├── Models/
│ └── Pizza.cs
├── Services/
│ └── PizzaService.cs
├── Program.cs
├── appsettings.json
└── README.md



## 🚀 API Endpoints

| Method | Route            | Beskrivning              |
|--------|------------------|--------------------------|
| GET    | `/pizza`         | Hämta alla pizzor        |
| GET    | `/pizza/{id}`    | Hämta en pizza efter ID  |
| PUT    | `/pizza/{id}`    | Uppdatera en pizza       |
| DELETE | `/pizza/{id}`    | Ta bort en pizza         |

köra projekt vs code 
dotnet run



