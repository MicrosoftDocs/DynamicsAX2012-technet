---
title: Employee.ChangePassword Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChangePassword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee.ChangePassword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employee.changepassword(v=AX.60)
ms:contentKeyID: 65316128
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee.ChangePassword
dev_langs:
- CSharp
- C++
- VB
---

# ChangePassword Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CHANGEPASSWORD")> _
Public Property ChangePassword As Boolean
    Get
    Set
'Usage
Dim instance As Employee
Dim value As Boolean

value = instance.ChangePassword

instance.ChangePassword = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CHANGEPASSWORD")]
public bool ChangePassword { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CHANGEPASSWORD")]
public:
property bool ChangePassword {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[Employee Class](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

