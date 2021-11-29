---
title: ILineDisplayV1.DisplayItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: DisplayItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILineDisplayV1.DisplayItem(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ilinedisplayv1.displayitem(v=AX.60)
ms:contentKeyID: 47344475
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILineDisplayV1.DisplayItem
dev_langs:
- CSharp
- C++
- VB
---

# DisplayItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Displays sale line item on the line display.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub DisplayItem ( _
    saleLineItem As ISaleLineItem _
)
'Usage
Dim instance As ILineDisplayV1
Dim saleLineItem As ISaleLineItem

instance.DisplayItem(saleLineItem)
```

``` csharp
void DisplayItem(
    ISaleLineItem saleLineItem
)
```

``` c++
void DisplayItem(
    ISaleLineItem^ saleLineItem
)
```

#### Parameters

  - saleLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ILineDisplayV1 Interface](ilinedisplayv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

