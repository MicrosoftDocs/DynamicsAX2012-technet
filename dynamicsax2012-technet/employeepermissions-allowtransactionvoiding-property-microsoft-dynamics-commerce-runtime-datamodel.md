---
title: EmployeePermissions.AllowTransactionVoiding Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowTransactionVoiding Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowTransactionVoiding
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowtransactionvoiding(v=AX.60)
ms:contentKeyID: 62212972
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowTransactionVoiding
dev_langs:
- CSharp
- C++
- VB
---

# AllowTransactionVoiding Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether transaction voiding is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ALLOWTRANSACTIONVOIDING")> _
<RequiredAttribute> _
Public Property AllowTransactionVoiding As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowTransactionVoiding

instance.AllowTransactionVoiding = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("ALLOWTRANSACTIONVOIDING")]
[RequiredAttribute]
public bool AllowTransactionVoiding { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ALLOWTRANSACTIONVOIDING")]
[RequiredAttribute]
public:
property bool AllowTransactionVoiding {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[EmployeePermissions Class](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

