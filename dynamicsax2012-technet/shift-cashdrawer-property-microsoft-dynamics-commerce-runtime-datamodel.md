---
title: Shift.CashDrawer Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CashDrawer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.CashDrawer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.cashdrawer(v=AX.60)
ms:contentKeyID: 62214301
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.CashDrawer
dev_langs:
- CSharp
- C++
- VB
---

# CashDrawer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cash drawer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CASHDRAWER")> _
<DataMemberAttribute> _
Public Property CashDrawer As String
    Get
    Set
'Usage
Dim instance As Shift
Dim value As String

value = instance.CashDrawer

instance.CashDrawer = value
```

``` csharp
[ColumnAttribute("CASHDRAWER")]
[DataMemberAttribute]
public string CashDrawer { get; set; }
```

``` c++
[ColumnAttribute(L"CASHDRAWER")]
[DataMemberAttribute]
public:
property String^ CashDrawer {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

