---
title: IItemSystemV1.PriceOverrideRestrictions Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: PriceOverrideRestrictions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.PriceOverrideRestrictions(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iitemsystemv1.priceoverriderestrictions(v=AX.60)
ms:contentKeyID: 47128098
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.PriceOverrideRestrictions
dev_langs:
- CSharp
- C++
- VB
---

# PriceOverrideRestrictions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the employee price override restrictions.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function PriceOverrideRestrictions ( _
    staffId As String _
) As EmployeePriceOverride
'Usage
Dim instance As IItemSystemV1
Dim staffId As String
Dim returnValue As EmployeePriceOverride

returnValue = instance.PriceOverrideRestrictions(staffId)
```

``` csharp
EmployeePriceOverride PriceOverrideRestrictions(
    string staffId
)
```

``` c++
EmployeePriceOverride PriceOverrideRestrictions(
    String^ staffId
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.EmployeePriceOverride](employeepriceoverride-enumeration-microsoft-dynamics-retail-pos-contracts.md)  
The EmployeePriceOverride for the given staff id.  

## See Also

#### Reference

[IItemSystemV1 Interface](iitemsystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

