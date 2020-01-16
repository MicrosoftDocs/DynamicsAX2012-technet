---
title: TillLayout.Height Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Height Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.Height
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.height(v=AX.60)
ms:contentKeyID: 62213922
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.Height
dev_langs:
- CSharp
- C++
- VB
---

# Height Property

Gets or sets the value of screen height.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("HEIGHT")> _
Public Property Height As Integer
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As Integer

value = instance.Height

instance.Height = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("HEIGHT")]
public int Height { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"HEIGHT")]
public:
property int Height {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The screen height.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

