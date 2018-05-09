---
title: TenderLineBase.GiftCardId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GiftCardId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.GiftCardId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.giftcardid(v=AX.60)
ms:contentKeyID: 62212774
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.GiftCardId
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardId Property

Gets or sets gift card identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("GIFTCARDID")> _
<DataMemberAttribute> _
Public Property GiftCardId As String
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As String

value = instance.GiftCardId

instance.GiftCardId = value
```

``` csharp
[ColumnAttribute("GIFTCARDID")]
[DataMemberAttribute]
public string GiftCardId { get; set; }
```

``` c++
[ColumnAttribute(L"GIFTCARDID")]
[DataMemberAttribute]
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

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

