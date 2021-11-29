---
title: CartLine.IsVoided Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsVoided Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.IsVoided
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.isvoided(v=AX.60)
ms:contentKeyID: 62209395
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.IsVoided
dev_langs:
- CSharp
- C++
- VB
---

# IsVoided Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether this instance is voided.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsVoided As Boolean
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Boolean

value = instance.IsVoided

instance.IsVoided = value
```

``` csharp
[DataMemberAttribute]
public bool IsVoided { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsVoided {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if this instance is voided; otherwise, false.  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

