---
title: TokenizedPaymentCard.CardTokenInfo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardTokenInfo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard.CardTokenInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tokenizedpaymentcard.cardtokeninfo(v=AX.60)
ms:contentKeyID: 65318208
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard.CardTokenInfo
dev_langs:
- CSharp
- C++
- VB
---

# CardTokenInfo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the card token information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardTokenInfo As CardTokenInfo
    Get
    Set
'Usage
Dim instance As TokenizedPaymentCard
Dim value As CardTokenInfo

value = instance.CardTokenInfo

instance.CardTokenInfo = value
```

``` csharp
[DataMemberAttribute]
public CardTokenInfo CardTokenInfo { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CardTokenInfo^ CardTokenInfo {
    CardTokenInfo^ get ();
    void set (CardTokenInfo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTokenInfo](cardtokeninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The card token information.  

## See Also

#### Reference

[TokenizedPaymentCard Class](tokenizedpaymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

