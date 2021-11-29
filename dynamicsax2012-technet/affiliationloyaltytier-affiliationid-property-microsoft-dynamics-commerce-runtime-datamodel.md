---
title: AffiliationLoyaltyTier.AffiliationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AffiliationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AffiliationLoyaltyTier.AffiliationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.affiliationloyaltytier.affiliationid(v=AX.60)
ms:contentKeyID: 62207958
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AffiliationLoyaltyTier.AffiliationId
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the affiliation identifier associated with this transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("AFFILIATION")> _
Public Property AffiliationId As Long
    Get
    Set
'Usage
Dim instance As AffiliationLoyaltyTier
Dim value As Long

value = instance.AffiliationId

instance.AffiliationId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("AFFILIATION")]
public long AffiliationId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"AFFILIATION")]
public:
property long long AffiliationId {
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

