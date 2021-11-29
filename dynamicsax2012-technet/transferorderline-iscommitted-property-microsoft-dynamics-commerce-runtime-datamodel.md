---
title: TransferOrderLine.IsCommitted Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsCommitted Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.IsCommitted
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorderline.iscommitted(v=AX.60)
ms:contentKeyID: 62203512
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.IsCommitted
dev_langs:
- CSharp
- C++
- VB
---

# IsCommitted Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the line was updated in Ax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsCommitted As Boolean
    Get
    Set
'Usage
Dim instance As TransferOrderLine
Dim value As Boolean

value = instance.IsCommitted

instance.IsCommitted = value
```

``` csharp
[DataMemberAttribute]
public bool IsCommitted { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsCommitted {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrderLine Class](transferorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

