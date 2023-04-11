---
title: Cart.AffiliationLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AffiliationLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.AffiliationLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.affiliationlines(v=AX.60)
ms:contentKeyID: 62209851
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.AffiliationLines
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the affiliations on this cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AffiliationLines As IList(Of AffiliationLoyaltyTier)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As IList(Of AffiliationLoyaltyTier)

value = instance.AffiliationLines

instance.AffiliationLines = value
```

``` csharp
[DataMemberAttribute]
public IList<AffiliationLoyaltyTier> AffiliationLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<AffiliationLoyaltyTier^>^ AffiliationLines {
    IList<AffiliationLoyaltyTier^>^ get ();
    void set (IList<AffiliationLoyaltyTier^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[AffiliationLoyaltyTier](affiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

