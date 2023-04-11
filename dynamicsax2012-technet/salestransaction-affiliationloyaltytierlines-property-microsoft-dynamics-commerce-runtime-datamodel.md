---
title: SalesTransaction.AffiliationLoyaltyTierLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AffiliationLoyaltyTierLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.AffiliationLoyaltyTierLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.affiliationloyaltytierlines(v=AX.60)
ms:contentKeyID: 62213611
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.AffiliationLoyaltyTierLines
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationLoyaltyTierLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales affiliation or loyalty tier lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AffiliationLoyaltyTierLines As Collection(Of SalesAffiliationLoyaltyTier)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Collection(Of SalesAffiliationLoyaltyTier)

value = instance.AffiliationLoyaltyTierLines

instance.AffiliationLoyaltyTierLines = value
```

``` csharp
[DataMemberAttribute]
public Collection<SalesAffiliationLoyaltyTier> AffiliationLoyaltyTierLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<SalesAffiliationLoyaltyTier^>^ AffiliationLoyaltyTierLines {
    Collection<SalesAffiliationLoyaltyTier^>^ get ();
    void set (Collection<SalesAffiliationLoyaltyTier^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[SalesAffiliationLoyaltyTier](salesaffiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

