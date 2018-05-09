---
title: OrderManager.CreatePackingSlip Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: CreatePackingSlip Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.CreatePackingSlip(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.createpackingslip(v=AX.60)
ms:contentKeyID: 62202099
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.CreatePackingSlip
dev_langs:
- CSharp
- C++
- VB
---

# CreatePackingSlip Method

Executes the creation of a packing slip for a customer order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub CreatePackingSlip ( _
    salesId As String _
)
'Usage
Dim instance As OrderManager
Dim salesId As String

instance.CreatePackingSlip(salesId)
```

``` csharp
public void CreatePackingSlip(
    string salesId
)
```

``` c++
public:
void CreatePackingSlip(
    String^ salesId
)
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

