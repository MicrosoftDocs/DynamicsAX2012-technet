---
title: EmployeePermissions.MaximumTotalDiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumTotalDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.MaximumTotalDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.maximumtotaldiscountamount(v=AX.60)
ms:contentKeyID: 62209963
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.MaximumTotalDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# MaximumTotalDiscountAmount Property

Gets or sets a value indicating the maximum total discount amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
<ColumnAttribute("MAXTOTALDISCOUNTAMOUNT")> _
Public Property MaximumTotalDiscountAmount As Decimal
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Decimal

value = instance.MaximumTotalDiscountAmount

instance.MaximumTotalDiscountAmount = value
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute("MAXTOTALDISCOUNTAMOUNT")]
public decimal MaximumTotalDiscountAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute(L"MAXTOTALDISCOUNTAMOUNT")]
public:
property Decimal MaximumTotalDiscountAmount {
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

