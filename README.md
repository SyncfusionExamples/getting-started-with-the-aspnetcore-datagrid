# Getting Started with the ASP.NET Core Grid Control

## Repository Description

This repository provides a getting-started sample that demonstrates how to use the Syncfusion [ASP.NET Core DataGrid](https://www.syncfusion.com/aspnet-core-ui-controls/grid?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-datagrid-github-samples) control in a web application with common data presentation features enabled.

## Project Overview

This quick-start project showcases the basic setup and usage of the Syncfusion ASP.NET Core DataGrid within an ASP.NET Core Razor Pages application. The sample focuses on configuring grid columns and enabling commonly used features such as paging, sorting, filtering, and grouping. It is designed to help developers understand how to bind data to the grid, define columns declaratively, and enable built-in functionalities with minimal configuration.

The application uses a simple in-memory data source generated in the page model and binds it to the grid in the Razor view. This approach keeps the sample lightweight while clearly illustrating how the grid integrates with ASP.NET Core projects.

## Key Features

- [Data binding](https://ej2.syncfusion.com/aspnetcore/documentation/grid/data-binding/data-binding?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-datagrid-github-samples) using Razor Pages
- [Column](https://ej2.syncfusion.com/aspnetcore/documentation/grid/columns/columns?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-datagrid-github-samples) configuration with headers, formats, and alignment
- Built-in [paging](https://ej2.syncfusion.com/aspnetcore/documentation/grid/paging?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-datagrid-github-samples) support
- [Sorting](https://ej2.syncfusion.com/aspnetcore/documentation/grid/sorting?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-datagrid-github-samples), [filtering](https://ej2.syncfusion.com/aspnetcore/documentation/grid/filtering/filtering?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-datagrid-github-samples), and [grouping](https://ej2.syncfusion.com/aspnetcore/documentation/grid/grouping/grouping?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-datagrid-github-samples) enabled
- Minimal setup for quick learning and experimentation

## Project Prerequisites

Make sure you have compatible versions of the following IDE and framework installed on your machine before starting this project:

- .NET SDK 6.0
- Visual Studio 2022 or later

## Running the Application

Follow the steps below to clone the repository, restore dependencies, and run the application.

1. Clone the repository and navigate to the project directory:

   ```bash
   git clone https://github.com/SyncfusionExamples/getting-started-with-the-aspnetcore-datagrid.git
   cd getting-started-with-the-aspnetcore-datagrid
   ```

2. Restore the required NuGet packages:

   ```bash
   dotnet restore
   ```

3. Run the application using the .NET CLI or Visual Studio:

   ```bash
   dotnet run
   ```

After the application starts, launch the displayed application URL in a browser. The DataGrid will render with paging, sorting, filtering, and grouping enabled, displaying sample order data.

## Usage Notes

You can customize the grid by modifying column definitions in the Razor page or by updating the sample data generated in the page model. These changes help explore how different grid features behave with various configurations.

## Additional Resources

- [Syncfusion ASP.NET Core Grid Documentation](https://ej2.syncfusion.com/aspnetcore/documentation/grid/getting-started-core?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-datagrid-github-samples)
- [Syncfusion ASP.NET Core Demos](https://ej2.syncfusion.com/aspnetcore/grid/defaultfunctionalities#/bootstrap5?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-datagrid-github-samples)
- [System Requirements for ASP .NET Core EJ2 Components](https://ej2.syncfusion.com/aspnetcore/documentation/system-requirements?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-datagrid-github-samples)
