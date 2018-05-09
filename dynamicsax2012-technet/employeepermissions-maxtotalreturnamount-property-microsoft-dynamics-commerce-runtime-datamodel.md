---
title: EmployeePermissions.MaxTotalReturnAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaxTotalReturnAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.MaxTotalReturnAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.maxtotalreturnamount(v=AX.60)
ms:contentKeyID: 62209410
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.MaxTotalReturnAmount
dev_langs:
- CSharp
- C++
- VB
---

# MaxTotalReturnAmount Property

Gets or sets a value indicating the maximum total return amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
<ColumnAttribute("MAXTOTALRETURNAMOUNT")> _
Public Property MaxTotalReturnAmount As Decimal
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Decimal

value = instance.MaxTotalReturnAmount

instance.MaxTotalReturnAmount = value
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute("MAXTOTALRETURNAMOUNT")]
public decimal MaxTotalReturnAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute(L"MAXTOTALRETURNAMOUNT")]
public:
property Decimal MaxTotalReturnAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[EmployeePermissions Class](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

