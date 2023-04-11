---
title: OrderManager.GetOrder Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetOrder(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getorder(v=AX.60)
ms:contentKeyID: 49826777
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the sales order matching the sales identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOrder ( _
    salesId As String _
) As SalesOrder
'Usage
Dim instance As OrderManager
Dim salesId As String
Dim returnValue As SalesOrder

returnValue = instance.GetOrder(salesId)
```

``` csharp
public SalesOrder GetOrder(
    string salesId
)
```

``` c++
public:
SalesOrder^ GetOrder(
    String^ salesId
)
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Sales order matching the sales identifier, if found; otherwise null.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

