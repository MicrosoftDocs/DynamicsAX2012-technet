---
title: IUtilityV2.CreatePharmacySalesLineItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreatePharmacySalesLineItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreatePharmacySalesLineItem(System.String,Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv2.createpharmacysaleslineitem(v=AX.60)
ms:contentKeyID: 49854463
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreatePharmacySalesLineItem
dev_langs:
- CSharp
- C++
- VB
---

# CreatePharmacySalesLineItem Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreatePharmacySalesLineItem ( _
    storeCurrencyCode As String, _
    rounding As IRounding, _
    transaction As IPosTransaction _
) As IPharmacySalesLineItem
'Usage
Dim instance As IUtilityV2
Dim storeCurrencyCode As String
Dim rounding As IRounding
Dim transaction As IPosTransaction
Dim returnValue As IPharmacySalesLineItem

returnValue = instance.CreatePharmacySalesLineItem(storeCurrencyCode, _
    rounding, transaction)
```

``` csharp
IPharmacySalesLineItem CreatePharmacySalesLineItem(
    string storeCurrencyCode,
    IRounding rounding,
    IPosTransaction transaction
)
```

``` c++
IPharmacySalesLineItem^ CreatePharmacySalesLineItem(
    String^ storeCurrencyCode, 
    IRounding^ rounding, 
    IPosTransaction^ transaction
)
```

#### Parameters

  - storeCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - rounding  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding](irounding-interface-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPharmacySalesLineItem](ipharmacysaleslineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IUtilityV2 Interface](iutilityv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

