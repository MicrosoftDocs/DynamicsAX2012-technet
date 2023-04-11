---
title: AffiliationLoyaltyTier.LoyaltyTierId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyTierId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AffiliationLoyaltyTier.LoyaltyTierId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.affiliationloyaltytier.loyaltytierid(v=AX.60)
ms:contentKeyID: 62215042
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AffiliationLoyaltyTier.LoyaltyTierId
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyTierId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the loyalty tier identifier associated with this transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LOYALTYTIER")> _
<DataMemberAttribute> _
Public Property LoyaltyTierId As Long
    Get
    Set
'Usage
Dim instance As AffiliationLoyaltyTier
Dim value As Long

value = instance.LoyaltyTierId

instance.LoyaltyTierId = value
```

``` csharp
[ColumnAttribute("LOYALTYTIER")]
[DataMemberAttribute]
public long LoyaltyTierId { get; set; }
```

``` c++
[ColumnAttribute(L"LOYALTYTIER")]
[DataMemberAttribute]
public:
property long long LoyaltyTierId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[AffiliationLoyaltyTier Class](affiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

