---
title: OrderManager.GetGiftCard Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetGiftCard(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getgiftcard(v=AX.60)
ms:contentKeyID: 62209047
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# GetGiftCard Method

Gets the gift card information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetGiftCard ( _
    id As String _
) As GiftCard
'Usage
Dim instance As OrderManager
Dim id As String
Dim returnValue As GiftCard

returnValue = instance.GetGiftCard(id)
```

``` csharp
public GiftCard GetGiftCard(
    string id
)
```

``` c++
public:
GiftCard^ GetGiftCard(
    String^ id
)
```

#### Parameters

  - id  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.GiftCard](giftcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The gift card information.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

