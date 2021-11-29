---
title: CashDeclaration.CashType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CashType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CashDeclaration.CashType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cashdeclaration.cashtype(v=AX.60)
ms:contentKeyID: 62212904
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CashDeclaration.CashType
dev_langs:
- CSharp
- C++
- VB
---

# CashType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cash type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TYPE")> _
<IgnoreDataMemberAttribute> _
Public Property CashType As CashType
    Get
    Set
'Usage
Dim instance As CashDeclaration
Dim value As CashType

value = instance.CashType

instance.CashType = value
```

``` csharp
[ColumnAttribute("TYPE")]
[IgnoreDataMemberAttribute]
public CashType CashType { get; set; }
```

``` c++
[ColumnAttribute(L"TYPE")]
[IgnoreDataMemberAttribute]
public:
property CashType CashType {
    CashType get ();
    void set (CashType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CashType](cashtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CashType](cashtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CashDeclaration Class](cashdeclaration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

