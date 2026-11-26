# Syncfusion Blazor Server DataGrid - Exporting Customization

## Overview

This sample demonstrates export customization scenarios in the Syncfusion [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) for Blazor Server applications. The implementation focuses on modifying export behavior beyond the default Grid export workflow, including changing exported file names, exporting data without grouping information, and applying external filter criteria only during export operations. These customization techniques are useful when exported documents must follow business-specific rules that differ from the data currently displayed in the Grid. The sample provides a reference implementation for tailoring DataGrid export behavior while maintaining a standard user experience for end users.

## Features

- Demonstrates customization of Blazor DataGrid export operations.
- Shows how export output can use a custom file name instead of the default generated name.
- Demonstrates exporting data without grouped records.
- Shows how additional external filtering logic can be applied exclusively during export operations.
- Uses sample data and Grid configuration stored within the repository implementation.

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## How to run the project

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`ExportingCustomization.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd EJ2-DataGrid-BlazorServer-Exporting-Customization
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## Project structure

`Pages/` — contains the Blazor page that implements DataGrid export customization scenarios.

## Support and feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official Syncfusion DataGrid exporting documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/excel-exporting

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
