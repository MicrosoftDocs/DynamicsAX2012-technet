---
title: Customer.GetPrimaryAddress Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetPrimaryAddress Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.GetPrimaryAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.getprimaryaddress(v=AX.60)
ms:contentKeyID: 49833408
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.GetPrimaryAddress
dev_langs:
- CSharp
- C++
- VB
---

# GetPrimaryAddress Method

Gets the primary address for this customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetPrimaryAddress As Address
'Usage
Dim instance As Customer
Dim returnValue As Address

returnValue = instance.GetPrimaryAddress()
```

``` csharp
public Address GetPrimaryAddress()
```

``` c++
public:
Address^ GetPrimaryAddress()
```

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The customer address.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

