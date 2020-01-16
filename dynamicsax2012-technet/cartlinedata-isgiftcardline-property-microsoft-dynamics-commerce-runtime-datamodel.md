---
title: CartLineData.IsGiftCardLine Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsGiftCardLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsGiftCardLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.isgiftcardline(v=AX.60)
ms:contentKeyID: 62208007
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsGiftCardLine
dev_langs:
- CSharp
- C++
- VB
---

# IsGiftCardLine Property

Gets or sets a value indicating whether this instance is a gift card line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("GIFTCARD")> _
Public Property IsGiftCardLine As Boolean
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Boolean

value = instance.IsGiftCardLine

instance.IsGiftCardLine = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("GIFTCARD")]
public bool IsGiftCardLine { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"GIFTCARD")]
public:
property bool IsGiftCardLine {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

