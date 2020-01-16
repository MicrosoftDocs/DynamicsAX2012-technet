---
title: SalesTransaction.LoyaltyRewardPointLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyRewardPointLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.LoyaltyRewardPointLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.loyaltyrewardpointlines(v=AX.60)
ms:contentKeyID: 62209076
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.LoyaltyRewardPointLines
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyRewardPointLines Property

Gets or sets the reward point lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyRewardPointLines As Collection(Of LoyaltyRewardPointLine)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Collection(Of LoyaltyRewardPointLine)

value = instance.LoyaltyRewardPointLines

instance.LoyaltyRewardPointLines = value
```

``` csharp
[DataMemberAttribute]
public Collection<LoyaltyRewardPointLine> LoyaltyRewardPointLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<LoyaltyRewardPointLine^>^ LoyaltyRewardPointLines {
    Collection<LoyaltyRewardPointLine^>^ get ();
    void set (Collection<LoyaltyRewardPointLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[LoyaltyRewardPointLine](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

