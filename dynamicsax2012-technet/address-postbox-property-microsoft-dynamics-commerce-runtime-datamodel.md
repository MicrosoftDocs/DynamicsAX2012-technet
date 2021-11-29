---
title: Address.Postbox Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Postbox Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.Postbox
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.postbox(v=AX.60)
ms:contentKeyID: 62212221
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.Postbox
dev_langs:
- CSharp
- C++
- VB
---

# Postbox Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the post box.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("POSTBOX")> _
<DataMemberAttribute> _
Public Property Postbox As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.Postbox

instance.Postbox = value
```

``` csharp
[ColumnAttribute("POSTBOX")]
[DataMemberAttribute]
public string Postbox { get; set; }
```

``` c++
[ColumnAttribute(L"POSTBOX")]
[DataMemberAttribute]
public:
property String^ Postbox {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

