---
title: IUtilityV5.CreateDiscountItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateDiscountItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV5.CreateDiscountItem(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.DiscountTypes,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv5.creatediscountitem(v=AX.60)
ms:contentKeyID: 62204117
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV5.CreateDiscountItem
dev_langs:
- CSharp
- C++
- VB
---

# CreateDiscountItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Create discount item based on discount type.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateDiscountItem ( _
    discountType As DiscountTypes, _
    isManualTotal As Boolean _
) As IDiscountItem
'Usage
Dim instance As IUtilityV5
Dim discountType As DiscountTypes
Dim isManualTotal As Boolean
Dim returnValue As IDiscountItem

returnValue = instance.CreateDiscountItem(discountType, _
    isManualTotal)
```

``` csharp
IDiscountItem CreateDiscountItem(
    DiscountTypes discountType,
    bool isManualTotal
)
```

``` c++
IDiscountItem^ CreateDiscountItem(
    DiscountTypes discountType, 
    bool isManualTotal
)
```

#### Parameters

  - discountType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.DiscountTypes](discounttypes-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - isManualTotal  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDiscountItem](idiscountitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
return the object created  

## See Also

#### Reference

[IUtilityV5 Interface](iutilityv5-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

