dotnet new sln --name auth

dotnet new webapi --name auth.api

dotnet new gitignore

dotnet sln add ./src/auth.api/auth.api.csproj

dotnet new mvc --name auth.presentation

dotnet sln add ./src/auth.presentation/auth.presentation.csproj