---
title: IncomeExpenseLine.Shift Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Shift Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseLine.Shift
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.incomeexpenseline.shift(v=AX.60)
ms:contentKeyID: 62214613
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseLine.Shift
dev_langs:
- CSharp
- C++
- VB
---

# Shift Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shift value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SHIFT")> _
<DataMemberAttribute> _
Public Property Shift As String
    Get
    Set
'Usage
Dim instance As IncomeExpenseLine
Dim value As String

value = instance.Shift

instance.Shift = value
```

``` csharp
[ColumnAttribute("SHIFT")]
[DataMemberAttribute]
public string Shift { get; set; }
```

``` c++
[ColumnAttribute(L"SHIFT")]
[DataMemberAttribute]
public:
property String^ Shift {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IncomeExpenseLine Class](incomeexpenseline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

