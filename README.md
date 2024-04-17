# umbraco-14-rc


```bash
# Ensure we have the version specific Umbraco templates
dotnet new install Umbraco.Templates::14.0.0-rc1 --force

# Create solution/project
dotnet new sln --name "UmbRc14TestSolution"
dotnet new umbraco --force -n "UmbRc14TestProject" --friendly-name "Administrator" --email "" --password "" --development-database-type SQLite
dotnet sln add "UmbRc14TestProject"

dotnet run --project "UmbRc14TestProject"
#Running
```