# Phoneword

Phoneword is a .NET MAUI application that translates a word into its corresponding phone number.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Components](#components)
  - [App.xaml](#appxaml)
  - [App.xaml.cs](#appxamlcs)
  - [AppShell.xaml](#appshellxaml)
  - [AppShell.xaml.cs](#appshellxamlcs)
  - [MainPage.xaml](#mainpagexaml)
  - [MainPage.xaml.cs](#mainpagexamlcs)
  - [MauiProgram.cs](#mauiprogramcs)
  - [PhonewordTranslator.cs](#phonewordtranslatorcs)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Phoneword.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Phoneword
    ```
3. Restore the necessary packages:
    ```bash
    dotnet restore
    ```
4. Build the project:
    ```bash
    dotnet build
    ```

## Usage

1. Run the application:
    ```bash
    dotnet run
    ```
2. Enter a word in the input field to see its corresponding phone number.

## Project Structure

```plaintext
Phoneword/
├── App.xaml
├── App.xaml.cs
├── AppShell.xaml
├── AppShell.xaml.cs
├── MainPage.xaml
├── MainPage.xaml.cs
├── MauiProgram.cs
├── Phoneword.csproj
├── Phoneword.csproj.user
├── PhonewordTranslator.cs
└── README.md
```
## Components

### App.xaml
The `App.xaml` file defines the root resources and styles for the application.

### App.xaml.cs
The `App.xaml.cs` file contains the code-behind logic for the `App.xaml` file. It initializes the application and sets up the main page.

### AppShell.xaml
The `AppShell.xaml` file defines the visual structure of the application using Shell. It sets up the routes and navigation structure.

### AppShell.xaml.cs
The `AppShell.xaml.cs` file contains the code-behind logic for the `AppShell.xaml` file.

### MainPage.xaml
The `MainPage.xaml` file defines the UI for the main page of the application, where users can input a word to translate.

### MainPage.xaml.cs
The `MainPage.xaml.cs` file contains the code-behind logic for the `MainPage.xaml` file, managing the main page's user interactions and data binding.

### MauiProgram.cs
The `MauiProgram.cs` file sets up the MAUI application, configuring services and the app builder.

### PhonewordTranslator.cs
The `PhonewordTranslator.cs` file contains the logic to translate a word into its corresponding phone number.
