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



To add the step of changing the folder structure to adopt the new one: Components > Layouts > Pages > UI, follow these steps:

1. Open your project in your preferred code editor.

2. Navigate to the `src/WebApp` directory.

3. Create a new folder called `Components` inside the `src/WebApp` directory.

4. Inside the `Components` folder, create a new folder called `Layouts`.

5. Inside the `Layouts` folder, create a new folder called `Pages`.

6. Inside the `Pages` folder, create a new folder called `UI`.

7. Move the `App.razor` file and `_imports.razor` file into the `UI` folder.

8. Save the changes.

Now your folder structure should be updated to the new one: Components > Layouts > Pages > UI.

Note: By organizing the `App.razor` and `_Imports.razor` files into the `UI` folder within the `Pages` folder, you are tidying up the `WebApp` project structure. This helps to maintain a clean and organized codebase, making it easier to navigate and manage your components.

Additionally, it is recommended to follow a consistent folder structure convention, such as the one mentioned in the previous step: Components > Layouts > Pages > UI. This convention provides a logical organization of your components, layouts, and pages, improving code readability and maintainability.

Remember to update any references to the `App.razor` file and `_Imports.razor` file in your project to reflect the new folder structure.

Continue with the next steps to complete the project setup.

Continue with the next steps to complete the project setup.