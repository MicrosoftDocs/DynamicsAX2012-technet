---
title: ButtonGridButton.Column Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Column Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.Column
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.column(v=AX.60)
ms:contentKeyID: 62202915
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.Column
dev_langs:
- CSharp
- C++
- VB
---

# Column Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the button column index.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COL")> _
Public Property Column As Integer
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As Integer

value = instance.Column

instance.Column = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COL")]
public int Column { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COL")]
public:
property int Column {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The button column index.  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

