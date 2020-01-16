---
title: ReasonCodeLine.IsChanged Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsChanged Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.IsChanged
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.ischanged(v=AX.60)
ms:contentKeyID: 62205729
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.IsChanged
dev_langs:
- CSharp
- C++
- VB
---

# IsChanged Property

Gets or sets a value indicating whether this instance is changed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsChanged As Boolean
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As Boolean

value = instance.IsChanged

instance.IsChanged = value
```

``` csharp
[DataMemberAttribute]
public bool IsChanged { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsChanged {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if this instance is changed; otherwise, false.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

