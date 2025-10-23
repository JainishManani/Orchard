# Deployment Instructions
1. Deploy to Azure App Service (Windows, .NET 4.8).
2. Configure Azure SQL Database.
3. Update web.config with connection string.

# Orchard CMS Deployment
## Build Instructions
1. Clone: `git clone https://github.com/JainishManani/Orchard.git`
2. Open `Orchard.sln` in Visual Studio 2022.
3. Restore NuGet packages (Tools > NuGet Package Manager > Restore).
4. Use SQLite for local DB or configure SQL Server in web.config.
5. Run (F5); complete setup wizard.