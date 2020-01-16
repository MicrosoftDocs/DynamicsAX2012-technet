---
title: CardTokenInfo.MaskedCardNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaskedCardNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTokenInfo.MaskedCardNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cardtokeninfo.maskedcardnumber(v=AX.60)
ms:contentKeyID: 65322510
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTokenInfo.MaskedCardNumber
dev_langs:
- CSharp
- C++
- VB
---

# MaskedCardNumber Property

Gets or sets masked card number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property MaskedCardNumber As String
    Get
    Set
'Usage
Dim instance As CardTokenInfo
Dim value As String

value = instance.MaskedCardNumber

instance.MaskedCardNumber = value
```

``` csharp
[DataMemberAttribute]
public string MaskedCardNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ MaskedCardNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CardTokenInfo Class](cardtokeninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

