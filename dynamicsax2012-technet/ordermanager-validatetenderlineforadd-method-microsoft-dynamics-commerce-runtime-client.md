---
title: OrderManager.ValidateTenderLineForAdd Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: ValidateTenderLineForAdd Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.ValidateTenderLineForAdd(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.validatetenderlineforadd(v=AX.60)
ms:contentKeyID: 65316402
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.ValidateTenderLineForAdd
dev_langs:
- CSharp
- C++
- VB
---

# ValidateTenderLineForAdd Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub ValidateTenderLineForAdd ( _
    cartId As String, _
    tenderLine As TenderLine _
)
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim tenderLine As TenderLine

instance.ValidateTenderLineForAdd(cartId, _
    tenderLine)
```

``` csharp
public void ValidateTenderLineForAdd(
    string cartId,
    TenderLine tenderLine
)
```

``` c++
public:
void ValidateTenderLineForAdd(
    String^ cartId, 
    TenderLine^ tenderLine
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

