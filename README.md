[![GitHub release](https://img.shields.io/github/release/dbol55/test1.svg)]() [![nuget](https://img.shields.io/nuget/v/Fortex.NET.SDK.svg)](https://www.nuget.org/packages/Fortex.NET.SDK/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

***

<img src="https://raw.githubusercontent.com/dbol55/test1/master/15.jpg" style="width:150%;">


## Fortnox .NET SDK
This is the official Fortnox .NET SDK for developing integrations towards the main Fortnox API. The package is not totally alaigned with the main API, but we are pretty close and will try to do conrurrent updates along with the main API. For more information please read our wiki were we have more code examples etc.

## Get started
* Register as a developer
* Read our package release information
* Install nuget package in Visual Studio
* Add reference to package FortnoxAPILibrary
* Start coding

```csharp
   var customerConnector = new CustomerConnector();
   var customer = new Customer();
   customer.CustomerNumber = "1";
   customer.Name = "Stefan Andersson";
   customerConnector.Create(customer);
```

```vbnet
   Dim customerConnector As New CustomerConnector()
   Dim customer As New Customer()
   customer.CustomerNumber = "1";
   customer.Name = "Stefan Andersson";
   customerConnector.Create(customer);
```

## Get help
* For help regarding this package please read our wiki for more information.
* For help that is not stated in our repository, please file a issue.
* For help regarding the main API please visit https://developer.fortnox.se/
* For help regarding release information please press here.







