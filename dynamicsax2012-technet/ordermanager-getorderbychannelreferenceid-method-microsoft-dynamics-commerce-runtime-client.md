---
title: OrderManager.GetOrderByChannelReferenceId Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOrderByChannelReferenceId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetOrderByChannelReferenceId(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getorderbychannelreferenceid(v=AX.60)
ms:contentKeyID: 62213283
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetOrderByChannelReferenceId
dev_langs:
- CSharp
- C++
- VB
---

# GetOrderByChannelReferenceId Method

Get the sales order matching the sales identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOrderByChannelReferenceId ( _
    channelReferenceId As String _
) As SalesOrder
'Usage
Dim instance As OrderManager
Dim channelReferenceId As String
Dim returnValue As SalesOrder

returnValue = instance.GetOrderByChannelReferenceId(channelReferenceId)
```

``` csharp
public SalesOrder GetOrderByChannelReferenceId(
    string channelReferenceId
)
```

``` c++
public:
SalesOrder^ GetOrderByChannelReferenceId(
    String^ channelReferenceId
)
```

#### Parameters

  - channelReferenceId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Sales order matching the sales identifier, if found; otherwise null.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

