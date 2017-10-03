[![GitHub release](https://img.shields.io/github/release/dbol55/test1.svg)]() [![nuget](https://img.shields.io/nuget/v/Fortex.NET.SDK.svg)](https://www.nuget.org/packages/Fortex.NET.SDK/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

***

<img src="https://raw.githubusercontent.com/dbol55/test1/master/15.jpg" style="width:150%;">


## Fortnox .NET SDK


## Get started
1) Register as a developer
2) Install nuget package in Visual Studio
3) Add reference to package FortnoxAPILibrary
   
```csharp
   try 
   {
      Customer customer = new Customer();
      customer.CustomerNumber = "1";
      customer.Name = "Stefan Andersson";
   } 
   catch (Exception ex) 
   { 
      Console.WriteLine(ex.Message); 
   } 
```







