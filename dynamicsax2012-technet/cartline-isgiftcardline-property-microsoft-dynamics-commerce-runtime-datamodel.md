---
title: CartLine.IsGiftCardLine Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsGiftCardLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.IsGiftCardLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.isgiftcardline(v=AX.60)
ms:contentKeyID: 62208729
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.IsGiftCardLine
dev_langs:
- CSharp
- C++
- VB
---

# IsGiftCardLine Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether this instance is a gift card line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsGiftCardLine As Boolean
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Boolean

value = instance.IsGiftCardLine

instance.IsGiftCardLine = value
```

``` csharp
[DataMemberAttribute]
public bool IsGiftCardLine { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsGiftCardLine {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if this instance is a gift card line; otherwise, false.  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

