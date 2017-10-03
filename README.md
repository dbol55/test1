[![GitHub release](https://img.shields.io/github/release/dbol55/test1.svg)]() [![nuget](https://img.shields.io/nuget/v/Fortex.NET.SDK.svg)](https://www.nuget.org/packages/Fortex.NET.SDK/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

***

<img src="https://raw.githubusercontent.com/dbol55/test1/master/15.jpg" style="width:150%;">


## Fortnox .NET SDK
This is the official Fortnox .NET SDK for developing integrations towards the main Fortnox API. 

This is a guide to help developers to get started with the .NET SDK by developing a simple console application which creates, retrives, deletes and search for a customer. For a full API reference please visit developer.fortnox.se/documentation/

## Get started
1) Register as a developer
2) Install nuget package in Visual Studio
3) Add reference to package FortnoxAPILibrary
4) Start coding

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
<br>
* For help that is not stated in our repository, please file a issue.
<br>
* For help regarding the main API please visit https://developer.fortnox.se/







