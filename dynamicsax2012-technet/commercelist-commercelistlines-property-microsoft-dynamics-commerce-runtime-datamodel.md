---
title: CommerceList.CommerceListLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CommerceListLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList.CommerceListLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.commercelist.commercelistlines(v=AX.60)
ms:contentKeyID: 62209743
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList.CommerceListLines
dev_langs:
- CSharp
- C++
- VB
---

# CommerceListLines Property

Gets or sets the commerce list lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CommerceListLines As IList(Of CommerceListLine)
    Get
    Set
'Usage
Dim instance As CommerceList
Dim value As IList(Of CommerceListLine)

value = instance.CommerceListLines

instance.CommerceListLines = value
```

``` csharp
[DataMemberAttribute]
public IList<CommerceListLine> CommerceListLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<CommerceListLine^>^ CommerceListLines {
    IList<CommerceListLine^>^ get ();
    void set (IList<CommerceListLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[CommerceListLine](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[CommerceList Class](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

