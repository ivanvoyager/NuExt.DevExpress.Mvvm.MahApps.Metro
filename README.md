# NuExt.DevExpress.Mvvm.MahApps.Metro
[![NuGet](https://img.shields.io/nuget/v/NuExt.DevExpress.Mvvm.MahApps.Metro.svg)](https://www.nuget.org/packages/NuExt.DevExpress.Mvvm.MahApps.Metro)
[![Build](https://github.com/ivanvoyager/NuExt.DevExpress.Mvvm.MahApps.Metro/actions/workflows/ci.yml/badge.svg)](https://github.com/ivanvoyager/NuExt.DevExpress.Mvvm.MahApps.Metro/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/ivanvoyager/NuExt.DevExpress.Mvvm.MahApps.Metro?label=license)](https://github.com/ivanvoyager/NuExt.DevExpress.Mvvm.MahApps.Metro/blob/main/LICENSE)
[![Downloads](https://img.shields.io/nuget/dt/NuExt.DevExpress.Mvvm.MahApps.Metro.svg)](https://www.nuget.org/packages/NuExt.DevExpress.Mvvm.MahApps.Metro)

`NuExt.DevExpress.Mvvm.MahApps.Metro` is a NuGet package that provides extensions for integrating [MahApps.Metro](https://github.com/MahApps/MahApps.Metro), a popular Metro-style UI toolkit for WPF applications, with the [DevExpress MVVM Framework](https://github.com/DevExpress/DevExpress.Mvvm.Free), a robust library designed to simplify and enhance the development of WPF applications using the Model-View-ViewModel (MVVM) pattern. This package includes services and components to facilitate the creation of modern, responsive, and visually appealing user interfaces using the MVVM pattern.

## Migration Note

If you are starting a new project or planning to modernize an existing one, consider using the **NuExt.Minimal.Mvvm.MahApps.Metro** and **NuExt.Minimal.Mvvm** family instead of this package.

`NuExt.Minimal.Mvvm`, `NuExt.Minimal.Behaviors.Wpf`, and `NuExt.Minimal.Mvvm.Wpf` provide a more streamlined and predictable MVVM model with:

- a minimal and dependency‑free core,
- deterministic async command semantics,
- lightweight ViewModel lifecycles,
- explicit view/document/dialog composition,
- clean integration with modern .NET and multi‑UI‑thread WPF scenarios.

This package remains functional and stable for existing applications, but the **NuExt.Minimal.Mvvm.MahApps.Metro** is recommended for new development.

Learn more:
- https://www.nuget.org/packages/NuExt.Minimal.Mvvm  
- https://www.nuget.org/packages/NuExt.Minimal.Behaviors.Wpf  
- https://www.nuget.org/packages/NuExt.Minimal.Mvvm.Wpf  
- https://www.nuget.org/packages/NuExt.Minimal.Mvvm.MahApps.Metro

### Commonly Used Types

- **`DevExpress.Mvvm.UI.DialogCoordinatorService`**: Provides dialog coordination services using MahApps.Metro dialogs.
- **`DevExpress.Mvvm.UI.MetroDialogService`**: `IAsyncDialogService` implementation for Metro dialogs.
- **`DevExpress.Mvvm.UI.MetroTabbedDocumentUIService`**: Manages tabbed documents within a UI.
- **`MahApps.Metro.Controls.Dialogs.MetroDialog`**: The class used for custom dialogs.

### Key Features

The `MetroTabbedDocumentUIService` class is responsible for managing tabbed documents within a UI that utilizes the Metro design language. It extends the `DocumentUIServiceBase` and implements interfaces for asynchronous document management and disposal. This service allows for the creation, binding, and lifecycle management of tabbed documents within controls such as `MetroTabControl`, `UserControl`, and `Window`.

### Installation

You can install `NuExt.DevExpress.Mvvm.MahApps.Metro` via [NuGet](https://www.nuget.org/):

```sh
dotnet add package NuExt.DevExpress.Mvvm.MahApps.Metro
```

Or through the Visual Studio package manager:

1. Go to `Tools -> NuGet Package Manager -> Manage NuGet Packages for Solution...`.
2. Search for `NuExt.DevExpress.Mvvm.MahApps.Metro`.
3. Click "Install".

### Usage Examples

For comprehensive examples of how to use the package, refer to the [MetroWpfApp](https://github.com/ivanvoyager/NuExt.DevExpress.Mvvm.MahApps.Metro/tree/main/samples/MetroWpfApp).

### Contributing

Contributions are welcome! Feel free to submit issues, fork the repository, and send pull requests. Your feedback and suggestions for improvement are highly appreciated.

### License

Licensed under the MIT License. See the LICENSE file for details.