# playwright-specflow-pom-dotnet

This project is for the purpose of showing a working example of how to use Playwright with SpecFlow and Page Object Models (POM) in .NET (C#).

It has been created to complement a blog post which gives a step-by-step guide on creating a new test project using Playwright/SpecFlow/POM. 
Find this on the Hippo Digital Medium blog: 

[How to use Playwright with SpecFlow and Page Object Models in .NET (C#) - Medium](https://medium.com/hippo-digital/how-to-use-playwright-with-specflow-and-page-object-models-in-net-c-708a0fd6ec5)

## Run the project locally
### 1. Checkout the project
`git clone git@github.com:hippo-digital/playwright-specflow-pom-dotnet-c.git`

### 2. Install NuGet packages
`nuget restore ` (at project root)

### 3. Run the tests
From terminal: `dotnet test` (at project root)

Or using the test controls in your IDE

If you need to install pwsh, use this command:
dotnet tool install --global PowerShell
