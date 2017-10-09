[![GitHub release](https://img.shields.io/github/release/dbol55/test1.svg)]() [![nuget](https://img.shields.io/nuget/v/Fortex.NET.SDK.svg)](https://www.nuget.org/packages/Fortex.NET.SDK/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

***

<img src="https://raw.githubusercontent.com/dbol55/test1/master/15.jpg" style="width:150%;">


## Fortnox .NET SDK
Official .NET SDK for developing integrations towards Fortnox API. Please note that this package is not totally aligned with the main API, however we are pretty close and will strive to keep up the pace. For more information and full documentation please visit developer.

## Get started
* Register as <a href="https://developer.fortnox.se/" target="_blank">developer</a>
* Install nuget package Fortnox.NET.SDK
* Start coding

```CSharp
   var customerConnector = new CustomerConnector();
   var customer = new Customer();
   customer.CustomerNumber = "1";
   customer.Name = "Stefan Andersson";
   customerConnector.Create(customer);
```

´´´VB
   Dim customerConnector As New CustomerConnector()
   Dim customer As New Customer()
   customer.CustomerNumber = "1";
   customer.Name = "Stefan Andersson";
   customerConnector.Create(customer);
```

## Get help
* For Help regarding this package and code examples visit our <a href="https://developer.fortnox.se/">wiki</a>.
* For help regarding the main API please visit https://developer.fortnox.se/
* For help regarding release information visit our <a href="https://developer.fortnox.se/">changelog</a>.
* For other help about our package please file a <a href="https://developer.fortnox.se/">issue</a>.

## Get licensed
The MIT License (MIT)

Copyright (c) 2017 Fortnox AB, Jesper Svensson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: 

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.







