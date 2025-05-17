# FinShark - ASP.NET Core Web API

FinShark is an educational ASP.NET Core Web API project based on the tutorial series by Raw Coding on YouTube. It demonstrates modern API development practices using .NET Core and Entity Framework.

## 🔗 Tutorial Source

This project follows the YouTube tutorial series by [Raw Coding](https://www.youtube.com/@RawCoding):

**Watch here**: [ASP.NET Core Web API Course](https://www.youtube.com/watch?v=qBTe6uHJS_Y&list=PL82C6-O4XrHfrGOCPmKmwTO7M0avXyQKc)

## 🛠 Tech Stack

- ASP.NET Core 9
- C#
- Entity Framework Core
- RESTful API
- Swagger / OpenAPI

## 🚀 Getting Started

### Prerequisites

- [.NET SDK 9 or later](https://dotnet.microsoft.com/download)
- Visual Studio or VS Code with C# extension
- SQL Server or SQLite (depending on your setup)

### Installation

```bash
git clone https://github.com/mostafijur566/fin_shark.git
cd FinShark/api
dotnet restore
dotnet ef database update   # If using Entity Framework
dotnet run
