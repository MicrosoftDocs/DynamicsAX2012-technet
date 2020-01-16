---
title: ReasonCodeLine.ItemTender Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemTender Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.ItemTender
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.itemtender(v=AX.60)
ms:contentKeyID: 62212083
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.ItemTender
dev_langs:
- CSharp
- C++
- VB
---

# ItemTender Property

Gets or sets the item tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ITEMTENDER")> _
Public Property ItemTender As String
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As String

value = instance.ItemTender

instance.ItemTender = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ITEMTENDER")]
public string ItemTender { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ITEMTENDER")]
public:
property String^ ItemTender {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The item tender.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

