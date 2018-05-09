---
title: ProductRules.MustKeyInComment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MustKeyInComment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.MustKeyInComment
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.mustkeyincomment(v=AX.60)
ms:contentKeyID: 62214852
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.MustKeyInComment
dev_langs:
- CSharp
- C++
- VB
---

# MustKeyInComment Property

Gets a value indicating whether the product requires a comment to be specified upon selling.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MUSTKEYINCOMMENT")> _
<DataMemberAttribute> _
Public Property MustKeyInComment As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As Boolean

value = instance.MustKeyInComment
```

``` csharp
[ColumnAttribute("MUSTKEYINCOMMENT")]
[DataMemberAttribute]
public bool MustKeyInComment { get; internal set; }
```

``` c++
[ColumnAttribute(L"MUSTKEYINCOMMENT")]
[DataMemberAttribute]
public:
property bool MustKeyInComment {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ProductRules Class](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

