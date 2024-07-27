# Setting up the Project
To set up your project using Blazor WebAssembly, follow these steps:

1. Open your terminal or command prompt.

2. Run the following command to create a new Blazor WebAssembly project:

```shell
dotnet new blazorwasm -o src/WebApp -f net8.0 -au IndividualB2C -e
```

This command creates a new Blazor WebAssembly project with the specified options:
- `-o src/WebApp` sets the output directory to `src/WebApp`.
- `-f net8.0` specifies the target framework as .NET 8.0.
- `-au IndividualB2C` enables Azure Active Directory B2C authentication.
- `-e` generates an example authentication configuration.

To create a component for the NavMenu, follow these steps:

1. In the `src/WebApp` directory, create a new file called `NavMenu.razor`.

2. Open the `NavMenu.razor` file and add the provided code.

3. Save the `NavMenu.razor` file.

4. In your `App.razor` file, replace the existing `<NavMenu>` component with the provided code.

5. Save the `App.razor` file.

Now you have created a NavMenu component that displays a navigation bar with links to the home, counter, and fetch data pages. Customize the links and styling as needed.

Continue with the next steps to complete the project setup.
To add the step of adding the `NavMenu` component to the `MainLayout.razor` file, follow these steps:

1. Open the `MainLayout.razor` file in your project.

2. Locate the `<main>` element within the file.

3. Inside the `<main>` element, add the following code:

```razor
<NavMenu />
```

4. Save the `MainLayout.razor` file.

Now the `NavMenu` component will be included in the layout of your application, allowing the navigation bar to be displayed on all pages.

Continue with the next steps to complete the project setup.