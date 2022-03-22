 # Hamster Blog

 Following [Learn how to deploy .NET Core apps to Azure with GitHub Actions](https://docs.microsoft.com/en-us/shows/Azure-Friday/Learn-how-to-deploy-NET-Core-apps-to-Azure-with-GitHub-Actions) tutorial
 - Create project with `dotnet new webapp -f netcoreapp3.1 -o hamsterblog` 
 - Run project with `dotnet run` as per [Using .NET Core in VS Code](https://code.visualstudio.com/docs/languages/dotnet)
 - Add the project to github, possibly by using Visual Studio
 - Add a .github/workflows directory and a build-and-deploy.yml 
 - Tasks (Azure DevOps) = Jobs and Steps (Github Actions)
 - ${{ }} means you can refer to global variables
  - Can be set in github or in the env area of .yml
 - The runtime in Azure is assumed to be preconfigured (17:00)
  - Have to retrieve the 'publish profile' (17:30) from Azure and put into 'secrets' in Github (19:30)
 - 
