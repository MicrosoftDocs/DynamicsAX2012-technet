---
title: CustomerOrderInfo.ToXml Method  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: ToXml Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.ToXml
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.toxml(v=AX.60)
ms:contentKeyID: 62211774
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.ToXml
dev_langs:
- CSharp
- C++
- VB
---

# ToXml Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Serializes the current customer order information to XML.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function ToXml As String
'Usage
Dim instance As CustomerOrderInfo
Dim returnValue As String

returnValue = instance.ToXml()
```

``` csharp
public string ToXml()
```

``` c++
public:
String^ ToXml()
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The object in XML format.  

## See Also

#### Reference

[CustomerOrderInfo Class](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

