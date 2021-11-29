---
title: ButtonGridButton.Row Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Row Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.Row
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.row(v=AX.60)
ms:contentKeyID: 62206316
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.Row
dev_langs:
- CSharp
- C++
- VB
---

# Row Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the button's row index.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ROWNUM")> _
Public Property Row As Integer
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As Integer

value = instance.Row

instance.Row = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ROWNUM")]
public int Row { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ROWNUM")]
public:
property int Row {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The button's row index.  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

