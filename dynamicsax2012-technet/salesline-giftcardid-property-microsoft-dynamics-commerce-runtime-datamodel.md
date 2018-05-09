---
title: SalesLine.GiftCardId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GiftCardId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.GiftCardId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.giftcardid(v=AX.60)
ms:contentKeyID: 62214759
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.GiftCardId
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardId Property

Gets or sets the gift card identifier if this instance is a gift card line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ReadOnlyAttribute("GIFTCARDID")> _
<ColumnAttribute("GIFTCARDID")> _
Public Property GiftCardId As String
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As String

value = instance.GiftCardId

instance.GiftCardId = value
```

``` csharp
[DataMemberAttribute]
[ReadOnlyAttribute("GIFTCARDID")]
[ColumnAttribute("GIFTCARDID")]
public string GiftCardId { get; set; }
```

``` c++
[DataMemberAttribute]
[ReadOnlyAttribute(L"GIFTCARDID")]
[ColumnAttribute(L"GIFTCARDID")]
public:
property String^ GiftCardId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

