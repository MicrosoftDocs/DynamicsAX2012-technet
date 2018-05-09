---
title: CardTokenInfo.CardToken Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTokenInfo.CardToken
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cardtokeninfo.cardtoken(v=AX.60)
ms:contentKeyID: 65321893
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTokenInfo.CardToken
dev_langs:
- CSharp
- C++
- VB
---

# CardToken Property

Gets or sets the payment card token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardToken As String
    Get
    Set
'Usage
Dim instance As CardTokenInfo
Dim value As String

value = instance.CardToken

instance.CardToken = value
```

``` csharp
[DataMemberAttribute]
public string CardToken { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CardToken {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CardTokenInfo Class](cardtokeninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

