---
title: IssueLoyaltyCardResponse.LoyaltyCard Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: LoyaltyCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.IssueLoyaltyCardResponse.LoyaltyCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.issueloyaltycardresponse.loyaltycard(v=AX.60)
ms:contentKeyID: 62209672
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.IssueLoyaltyCardResponse.LoyaltyCard
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCard Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the loyalty card number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCard As LoyaltyCard
    Get
    Private Set
'Usage
Dim instance As IssueLoyaltyCardResponse
Dim value As LoyaltyCard

value = instance.LoyaltyCard
```

``` csharp
[DataMemberAttribute]
public LoyaltyCard LoyaltyCard { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property LoyaltyCard^ LoyaltyCard {
    LoyaltyCard^ get ();
    private: void set (LoyaltyCard^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LoyaltyCard](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[IssueLoyaltyCardResponse Class](issueloyaltycardresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

