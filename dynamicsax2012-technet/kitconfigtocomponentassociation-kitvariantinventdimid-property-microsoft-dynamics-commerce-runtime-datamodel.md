---
title: KitConfigToComponentAssociation.KitVariantInventDimId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitVariantInventDimId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation.KitVariantInventDimId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitconfigtocomponentassociation.kitvariantinventdimid(v=AX.60)
ms:contentKeyID: 65317653
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation.KitVariantInventDimId
dev_langs:
- CSharp
- C++
- VB
---

# KitVariantInventDimId Property

Gets the inventory dimension identifier of the current kit variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTDIMID")> _
<DataMemberAttribute> _
Public Property KitVariantInventDimId As String
    Get
    Friend Set
'Usage
Dim instance As KitConfigToComponentAssociation
Dim value As String

value = instance.KitVariantInventDimId
```

``` csharp
[ColumnAttribute("INVENTDIMID")]
[DataMemberAttribute]
public string KitVariantInventDimId { get; internal set; }
```

``` c++
[ColumnAttribute(L"INVENTDIMID")]
[DataMemberAttribute]
public:
property String^ KitVariantInventDimId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[KitConfigToComponentAssociation Class](kitconfigtocomponentassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

