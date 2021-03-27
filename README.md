# Exploring Blazor hybrid apps using Mobile Blazor Bindings with Syncfusion Blazor components

The [Mobile Blazor Bindings](https://docs.microsoft.com/en-us/mobile-blazor-bindings/) is an experimental project which allows developers to build native desktop and hybrid mobile apps using C# and .NET.

## Prerequisites

1.	[.NET SDK 3.1](https://dotnet.microsoft.com/download/) or Later
2.	Visual Studio with the following workloads
    -	ASP.NET and web development
    -	Mobile development with .NET
3.	The [Microsoft Edge Canary Channel](https://www.microsoftedgeinsider.com/en-us/download) is essential for running Blazor hybrid app on Windows.
    > Note: Without the above setup, the Blazor hybrid app will not work on Windows.

4.	Install the required project template by using below command line in command prompt.

    ```
    dotnet new -i Microsoft.MobileBlazorBindings.Templates::0.5.50-preview
    ```

## How to run the application?

* Open the `~/BlazorHybridApp/BlazorHybridApp.sln` file in the Visual Studio 2019.
* Set any platform specific project as a startup project and run the application.
* The Syncfusion Blazor component will be exposed in the native desktop or hybrid mobile layout.

## Blog post 

* Refer to this [blog post](https://www.syncfusion.com/blogs/post/blazor-hybrid-apps-using-mobile-blazor-bindings.aspx) for more details.
