# MyMudBlazor

MyMudBlazor is a Blazor project that leverages MudBlazor, a Material Design component library for Blazor. This project is built on .NET 8 and uses interactive server components.

## Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/)

## Getting Started

### Installation

1. Clone the repository:
`git clone https://github.com/yourusername/MyMudBlazor.git`
2. Navigate to the project directory:
`cd MyMudBlazor`
3. Restore the dependencies:
`dotnet restore`

### Running the Application

1. Build the project:
`dotnet build`
2. Run the project:
`dotnet run`
3. Open your browser and navigate to `https://localhost:5001`.

## Project Structure

- `MyMudBlazor.csproj`: Project file containing project dependencies and target framework.
- `Program.cs`: Configures and runs the application.
- `Components/Pages/Error.razor`: Error page component displaying error details.

## Dependencies

- [MudBlazor](https://mudblazor.com/): A Material Design component library for Blazor.

## Configuration

### Error Handling

The project is configured to use a custom error page (`/Error`) when not in development mode. The error page displays the request ID and provides information about switching to the development environment for more detailed error information.

### MudBlazor Services

MudBlazor services are added in `Program.cs`:
`builder.Services.AddMudServices();`