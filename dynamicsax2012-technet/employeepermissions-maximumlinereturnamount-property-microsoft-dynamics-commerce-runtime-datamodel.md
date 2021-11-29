---
title: EmployeePermissions.MaximumLineReturnAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumLineReturnAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.MaximumLineReturnAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.maximumlinereturnamount(v=AX.60)
ms:contentKeyID: 62211709
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.MaximumLineReturnAmount
dev_langs:
- CSharp
- C++
- VB
---

# MaximumLineReturnAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating the maximum line return amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
<ColumnAttribute("MAXLINERETURNAMOUNT")> _
Public Property MaximumLineReturnAmount As Decimal
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Decimal

value = instance.MaximumLineReturnAmount

instance.MaximumLineReturnAmount = value
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute("MAXLINERETURNAMOUNT")]
public decimal MaximumLineReturnAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute(L"MAXLINERETURNAMOUNT")]
public:
property Decimal MaximumLineReturnAmount {
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

