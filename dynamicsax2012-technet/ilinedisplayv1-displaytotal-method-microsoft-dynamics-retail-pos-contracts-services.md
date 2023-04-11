---
title: ILineDisplayV1.DisplayTotal Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: DisplayTotal Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILineDisplayV1.DisplayTotal(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ilinedisplayv1.displaytotal(v=AX.60)
ms:contentKeyID: 47344507
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILineDisplayV1.DisplayTotal
dev_langs:
- CSharp
- C++
- VB
---

# DisplayTotal Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Display sales total on the line display.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub DisplayTotal ( _
    amount As String _
)
'Usage
Dim instance As ILineDisplayV1
Dim amount As String

instance.DisplayTotal(amount)
```

``` csharp
void DisplayTotal(
    string amount
)
```

``` c++
void DisplayTotal(
    String^ amount
)
```

#### Parameters

  - amount  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ILineDisplayV1 Interface](ilinedisplayv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

