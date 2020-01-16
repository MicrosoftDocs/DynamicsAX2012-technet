---
title: KitConfigToComponentAssociation.KitConfigId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitConfigId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation.KitConfigId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitconfigtocomponentassociation.kitconfigid(v=AX.60)
ms:contentKeyID: 65319535
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation.KitConfigId
dev_langs:
- CSharp
- C++
- VB
---

# KitConfigId Property

Gets the configuration identifier of the current kit variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CONFIGID")> _
Public Property KitConfigId As String
    Get
    Friend Set
'Usage
Dim instance As KitConfigToComponentAssociation
Dim value As String

value = instance.KitConfigId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CONFIGID")]
public string KitConfigId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CONFIGID")]
public:
property String^ KitConfigId {
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

