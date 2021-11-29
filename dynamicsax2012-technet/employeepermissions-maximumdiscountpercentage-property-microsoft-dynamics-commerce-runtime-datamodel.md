---
title: EmployeePermissions.MaximumDiscountPercentage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumDiscountPercentage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.MaximumDiscountPercentage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.maximumdiscountpercentage(v=AX.60)
ms:contentKeyID: 62212088
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.MaximumDiscountPercentage
dev_langs:
- CSharp
- C++
- VB
---

# MaximumDiscountPercentage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating the maximum discount percentage.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MAXIMUMDISCOUNTPCT")> _
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property MaximumDiscountPercentage As Decimal
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Decimal

value = instance.MaximumDiscountPercentage

instance.MaximumDiscountPercentage = value
```

``` csharp
[ColumnAttribute("MAXIMUMDISCOUNTPCT")]
[DataMemberAttribute]
[RequiredAttribute]
public decimal MaximumDiscountPercentage { get; set; }
```

``` c++
[ColumnAttribute(L"MAXIMUMDISCOUNTPCT")]
[DataMemberAttribute]
[RequiredAttribute]
public:
property Decimal MaximumDiscountPercentage {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[EmployeePermissions Class](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

