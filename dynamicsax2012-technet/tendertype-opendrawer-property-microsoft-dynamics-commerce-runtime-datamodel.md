---
title: TenderType.OpenDrawer Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OpenDrawer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.OpenDrawer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.opendrawer(v=AX.60)
ms:contentKeyID: 62212110
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.OpenDrawer
dev_langs:
- CSharp
- C++
- VB
---

# OpenDrawer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether to open drawer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OPENDRAWER")> _
Public Property OpenDrawer As Boolean
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Boolean

value = instance.OpenDrawer

instance.OpenDrawer = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OPENDRAWER")]
public bool OpenDrawer { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OPENDRAWER")]
public:
property bool OpenDrawer {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

