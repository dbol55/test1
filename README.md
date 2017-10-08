[![GitHub release](https://img.shields.io/github/release/dbol55/test1.svg)]() [![nuget](https://img.shields.io/nuget/v/Fortex.NET.SDK.svg)](https://www.nuget.org/packages/Fortex.NET.SDK/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

***

<img src="https://raw.githubusercontent.com/dbol55/test1/master/15.jpg" style="width:150%;">


## Fortnox .NET SDK
<span style="text-align: justify">This is the official Fortnox .NET SDK for developing integrations towards the main Fortnox API. The package is not totally alaigned with the main API, but we are pretty close and will try to do conrurrent updates along with the main API. For more information please read our wiki were we have more code examples etc.</span>

## Get started
* Register as a <a href="https://developer.fortnox.se/" target="_blank">developer</a>
* Take part of our <a href="https://developer.fortnox.se/">release information</a>
* Take part of <a href="https://developer.fortnox.se/">code examples</a>
* Install nuget package Fortnox.NET.SDK
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
* For help regarding the main API please visit https://developer.fortnox.se/
* For help regarding this package please read our <a href="https://developer.fortnox.se/" target="_blank">wiki</a>.
* For help that is not stated in our repository, please file a <a href="https://developer.fortnox.se/" target="_blank">issue</a>.
* For help regarding release information please read our <a href="https://developer.fortnox.se/" target="_blank">changelog</a>.

## Get licensed
The MIT License (MIT)

Copyright (c) 2017 Fortnox AB, Jesper Svensson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: 

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.







