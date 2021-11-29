---
title: IncomeExpenseLine.Terminal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Terminal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseLine.Terminal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.incomeexpenseline.terminal(v=AX.60)
ms:contentKeyID: 62210019
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseLine.Terminal
dev_langs:
- CSharp
- C++
- VB
---

# Terminal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the terminal value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TERMINAL")> _
Public Property Terminal As String
    Get
    Set
'Usage
Dim instance As IncomeExpenseLine
Dim value As String

value = instance.Terminal

instance.Terminal = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TERMINAL")]
public string Terminal { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TERMINAL")]
public:
property String^ Terminal {
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

