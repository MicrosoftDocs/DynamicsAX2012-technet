---
title: EmployeePermissions.AllowPriceOverride Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowPriceOverride Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowPriceOverride
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowpriceoverride(v=AX.60)
ms:contentKeyID: 62207647
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowPriceOverride
dev_langs:
- CSharp
- C++
- VB
---

# AllowPriceOverride Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether price override is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ALLOWPRICEOVERRIDE")> _
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property AllowPriceOverride As Integer
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Integer

value = instance.AllowPriceOverride

instance.AllowPriceOverride = value
```

``` csharp
[ColumnAttribute("ALLOWPRICEOVERRIDE")]
[DataMemberAttribute]
[RequiredAttribute]
public int AllowPriceOverride { get; set; }
```

``` c++
[ColumnAttribute(L"ALLOWPRICEOVERRIDE")]
[DataMemberAttribute]
[RequiredAttribute]
public:
property int AllowPriceOverride {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[EmployeePermissions Class](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

