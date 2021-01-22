---
title: ButtonGridButton.ButtonId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ButtonId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.ButtonId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.buttonid(v=AX.60)
ms:contentKeyID: 62213811
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.ButtonId
dev_langs:
- CSharp
- C++
- VB
---

# ButtonId Property

Gets or sets the button identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ID")> _
Public Property ButtonId As Integer
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As Integer

value = instance.ButtonId

instance.ButtonId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ID")]
public int ButtonId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ID")]
public:
property int ButtonId {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The button identifier.  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

