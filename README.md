# 🧱 GRRInnovations Clean Architecture Template

A **professional Clean Architecture solution template** for **ASP.NET Core (.NET 9)** — designed to help developers quickly scaffold scalable, maintainable, and testable applications following industry best practices.

Created by **GRRInnovations**.

---

## 🏗️ Overview

This template provides a complete **Clean Architecture** setup with a modular structure that clearly separates responsibilities between layers:

### **📦 Domain**
- Contains **Entities**, **Value Objects**, and **Domain Events**.  
- Represents the **core business logic** — independent from frameworks and external dependencies.

### **⚙️ Application**
- Contains **Use Cases**, **CQRS Handlers (Commands/Queries)**, and **Interfaces** for repositories or external services.  
- Uses **MediatR**, **FluentValidation**, and **AutoMapper** by default.

### **🗄️ Infrastructure**
- Implements persistence, caching, and message brokers.  
- Ready for **Entity Framework Core**, **Redis**, and **RabbitMQ**.  
- Can easily integrate with **Serilog**, **Prometheus**, and other observability tools.

### **🌐 API**
- The **presentation layer** of the system (ASP.NET Core Web API).  
- Includes Swagger (OpenAPI), middleware examples, logging setup, and dependency injection configuration.

---

## 🚀 Features

✅ Domain-Driven Design (DDD) principles  
✅ Layered Clean Architecture pattern  
✅ Support for Redis, RabbitMQ, EF Core  
✅ Ready for Observability (Serilog, Prometheus)  
✅ Unit & Integration Test support  
✅ Enterprise-grade folder organization

---

## 🧰 How to Use

Install the template globally:

```bash
dotnet new install GRRInnovations.CleanArchitecture.Template
```

```bash
dotnet new grr-cleanarch -n MyCleanApi
