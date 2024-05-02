# umbraco-14-rc


```bash
# Ensure we have the version specific Umbraco templates
dotnet new install Umbraco.Templates::14.0.0-rc2 --force

# Create solution/project
dotnet new sln --name "UmbRc14_rc2_TestSolution"
dotnet new umbraco --force -n "UmbRc14_rc2_TestProject" --friendly-name "Administrator" --email "" --password "1234567890@!" --development-database-type SQLite
dotnet sln UmbRc14_rc2_TestSolution.sln add "UmbRc14_rc2_TestProject"

dotnet run --project "UmbRc14_rc2_TestProject"
#Running
```