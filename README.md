[![Build Status](https://travis-ci.org/robisrob/gameoflivecsharp.svg?branch=master)](https://travis-ci.org/robisrob/gameoflivecsharp)

# Game of live

## Prerequisite
NET Core SDK 1.0.1

## Run application
- cd Application
- dotnet restore
- dotnet run
## Send request
- POST 
 - url: http://localhost:5000/api/gameoflife
 - headers: Content-Type: application/json
 - example body: [[false, false, true], [false, true, true], [false, false, false]]

## Run tests
- dotnet restore ./Domain.Tests/Domain.Tests.csproj
 - dotnet test ./Domain.Tests/Domain.Tests.csproj
 - dotnet restore ./Application.Tests/Application.Tests.csproj
 - dotnet test ./Application.Tests/Application.Tests.csproj
 
## Explanation game
https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life