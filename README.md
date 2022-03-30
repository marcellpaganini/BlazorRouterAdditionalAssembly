# BlazorRouterAdditionalAssembly 
## Built With  
* [C#](https://docs.microsoft.com/en-us/dotnet/csharp// "C# documentation")  
* [Blazor](https://docs.microsoft.com/en-us/aspnet/core/blazor/?view=aspnetcore-6.0/ "Blazor Documentation")  

## Getting Started  
### Prerequisites
* [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet/6.0 "Download .NET 6.0")  

### Project Setup (VS Code)
* C#  
  * Create Blazor Server project  
  ```bash
  dotnet new blazorserver -n Main
  ```  
  * Create a new component class library  
  ```bash
  dotnet new razorclasslib -n ComponentLibrary
  ```  
  * Add a component project reference to the main project  
  ```bash
  dotnet add Main/Main.csproj reference ComponentLibrary/ComponentLibrary.csproj
  ``` 

### Programming Topics practiced to get things done  
#### 1- AdditionalAssemblies (Blazor)  
Route to components from multiple assemblies.   