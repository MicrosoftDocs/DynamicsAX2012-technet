---
title: TaxableItem.TaxLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.TaxLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxableitem.taxlines(v=AX.60)
ms:contentKeyID: 49837909
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.TaxLines
dev_langs:
- CSharp
- C++
- VB
---

# TaxLines Property

Gets the tax lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TaxLines As Collection(Of TaxLine)
    Get
    Set
'Usage
Dim instance As TaxableItem
Dim value As Collection(Of TaxLine)

value = instance.TaxLines

instance.TaxLines = value
```

``` csharp
[DataMemberAttribute]
public Collection<TaxLine> TaxLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<TaxLine^>^ TaxLines {
    Collection<TaxLine^>^ get ();
    void set (Collection<TaxLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[TaxLine](taxline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[TaxableItem Class](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

