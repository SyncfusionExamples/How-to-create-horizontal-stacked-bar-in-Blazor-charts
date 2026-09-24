# How to Create a Horizontal Stacked Bar in Syncfusion Blazor Charts

## Overview

This sample demonstrates how to create a horizontal stacked bar chart using Syncfusion [Blazor Charts](https://www.syncfusion.com/blazor-components/blazor-charts). The implementation uses multiple stacking bar series bound to a shared data source, allowing related values to be displayed as horizontally stacked segments within each category.

The chart renders country-based categorical data and compares multiple values within a single horizontal bar. By using stacked bar series, the sample helps visualize individual contributions to the overall total for each category while maintaining an easy-to-read horizontal layout.

## Key Features

- Uses the `SfChart` component to render the chart.
- Configures `ChartPrimaryXAxis` with `ValueType="ValueType.Category"` for category-based axis rendering.
- Uses `ChartSeriesCollection` to host multiple chart series.
- Binds chart data through the `DataSource` property.
- Maps category values using the `XName` property.
- Maps numerical values using the `YName` property.
- Uses `Type="ChartSeriesType.StackingBar"` to create horizontal stacked bar series.
- Demonstrates multiple stacked series sharing the same data source.
- Uses a strongly typed `ChartData` model containing:
  - `X`
  - `YValue`
  - `YValue1`
- Displays comparative data for multiple categories including USA, GBR, CHN, UK, AUS, IND, DEN, and MEX.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone the repository.
2. Open the following project file directly in Visual Studio 2022:

   `HorizontalBar/HorizontalBar.csproj`

3. Restore the required NuGet packages.
4. Build the project.
5. Press `Ctrl+F5` to run the application.

**Visual Studio Code**

1. Clone the repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory.

```bash
cd HorizontalBar
dotnet restore
dotnet run
```

5. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

`HorizontalBar/Pages/Index.razor` - Demonstrates the horizontal stacked bar chart implementation using `SfChart`, `ChartSeriesCollection`, and multiple `ChartSeries` elements configured with `ChartSeriesType.StackingBar`.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Refer to the official Syncfusion stacked bar chart documentation: https://help.syncfusion.com/chart-sdk/blazor/charts/chart-types/stacked-bar

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.