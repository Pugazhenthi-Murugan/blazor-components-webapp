# Getting Started Examples with Blazor Web App Components

A collection of small Blazor example apps that demonstrate how to use Syncfusion Blazor components ([Chart](https://www.syncfusion.com/blazor-components/blazor-charts), [DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid), [RichTextEditor](https://www.syncfusion.com/blazor-components/blazor-rich-text-editor), [Scheduler](https://www.syncfusion.com/blazor-components/blazor-scheduler), and more) across hosting models (WASM, Server, SSR and Auto). These samples are intended to help you prototype and learn how components integrate into Blazor projects.

## Overview

This repository contains small, focused Blazor example applications that demonstrate how to integrate and use  Blazor components across different hosting models. The samples are intended for learning and rapid prototyping — explore the component usage in each sample's `Pages` and `Components` folders to see practical setups, data binding, and theming.

## Features

- **Multiple Syncfusion Components**: Chart, DataGrid, Rich Text Editor, and Scheduler examples.
- **Multiple Hosting Models**: 
  - **WASM (WebAssembly)**: Client-side rendering for interactive experiences.
  - **Server**: Server-side rendering with interactive features.
  - **SSR (Static Site Rendering)**: Static content rendering option.
  - **Auto**: Automatic selection based on context.
- **Lightweight demos** focused on each component with practical examples.
- **Theming examples** showing how to add theme CSS (e.g., `fluent.css`, `bootstrap.css`).
- **Pre-configured Program.cs** demonstrating `builder.Services.AddSyncfusionBlazor()` registration.
- **Component usage patterns** for data binding, event handling, and state management.
- **Ready-to-run solutions** with proper folder structure and configurations.


## Getting started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-components-webapp.git
cd "blazor-components-webapp"
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

- https://blazor.syncfusion.com/documentation/datagrid/getting-started-with-server-app
- https://blazor.syncfusion.com/documentation/rich-text-editor/getting-started-with-server-app
- https://blazor.syncfusion.com/documentation/scheduler/getting-started