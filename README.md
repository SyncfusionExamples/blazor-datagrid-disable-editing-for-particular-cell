# Blazor DataGrid - Disable Editing for Particular Cell

## Overview

This sample demonstrates how to disable editing for specific cells in a Syncfusion [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid). The example focuses on applying conditional editing behavior so that selected cells remain read-only while other grid cells continue to participate in normal editing operations. This approach is useful when business rules require only a subset of records or fields to be editable within the same DataGrid.

## Key Features

- Uses the Syncfusion Blazor DataGrid component to display editable tabular data.
- Demonstrates conditional logic that prevents editing for specific cells.
- Shows how individual cells can remain read-only while editing remains enabled elsewhere in the Grid.
- Illustrates customization of the Grid editing experience based on application requirements.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file from the `DisableEditing-Cell` project folder.
3. Restore all NuGet packages.
4. Set the startup project to `DisableEditing-Cell` if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory inside `DisableEditing-Cell`.

```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

- `DisableEditing-Cell/` — contains the Blazor application that demonstrates conditional cell-editing behavior.
- `DisableEditing-Cell/Pages/` — contains the page that renders the Syncfusion Blazor DataGrid sample. [VERIFY: exact page file]

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid editing documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/editing

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
