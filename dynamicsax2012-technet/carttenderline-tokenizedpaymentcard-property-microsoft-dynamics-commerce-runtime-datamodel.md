---
title: CartTenderLine.TokenizedPaymentCard Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TokenizedPaymentCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartTenderLine.TokenizedPaymentCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.carttenderline.tokenizedpaymentcard(v=AX.60)
ms:contentKeyID: 65322348
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartTenderLine.TokenizedPaymentCard
dev_langs:
- CSharp
- C++
- VB
---

# TokenizedPaymentCard Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TokenizedPaymentCard As TokenizedPaymentCard
    Get
    Set
'Usage
Dim instance As CartTenderLine
Dim value As TokenizedPaymentCard

value = instance.TokenizedPaymentCard

instance.TokenizedPaymentCard = value
```

``` csharp
[DataMemberAttribute]
public TokenizedPaymentCard TokenizedPaymentCard { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property TokenizedPaymentCard^ TokenizedPaymentCard {
    TokenizedPaymentCard^ get ();
    void set (TokenizedPaymentCard^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard](tokenizedpaymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CartTenderLine Class](carttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

