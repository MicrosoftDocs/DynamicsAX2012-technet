---
title: IUtilityV1.CreateBarcodeInfo Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateBarcodeInfo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.CreateBarcodeInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv1.createbarcodeinfo(v=AX.60)
ms:contentKeyID: 47128425
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.CreateBarcodeInfo
dev_langs:
- CSharp
- C++
- VB
---

# CreateBarcodeInfo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates an [IBarcodeInfo](ibarcodeinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) object.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateBarcodeInfo As IBarcodeInfo
'Usage
Dim instance As IUtilityV1
Dim returnValue As IBarcodeInfo

returnValue = instance.CreateBarcodeInfo()
```

``` csharp
IBarcodeInfo CreateBarcodeInfo()
```

``` c++
IBarcodeInfo^ CreateBarcodeInfo()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfo](ibarcodeinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The barcode info.  

## See Also

#### Reference

[IUtilityV1 Interface](iutilityv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

