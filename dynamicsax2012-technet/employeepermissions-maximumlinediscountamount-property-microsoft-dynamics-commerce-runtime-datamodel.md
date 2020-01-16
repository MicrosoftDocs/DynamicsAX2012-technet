---
title: EmployeePermissions.MaximumLineDiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumLineDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.MaximumLineDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.maximumlinediscountamount(v=AX.60)
ms:contentKeyID: 62213952
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.MaximumLineDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# MaximumLineDiscountAmount Property

Gets or sets a value indicating the maximum line discount amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
<ColumnAttribute("MAXLINEDISCOUNTAMOUNT")> _
Public Property MaximumLineDiscountAmount As Decimal
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Decimal

value = instance.MaximumLineDiscountAmount

instance.MaximumLineDiscountAmount = value
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute("MAXLINEDISCOUNTAMOUNT")]
public decimal MaximumLineDiscountAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute(L"MAXLINEDISCOUNTAMOUNT")]
public:
property Decimal MaximumLineDiscountAmount {
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

