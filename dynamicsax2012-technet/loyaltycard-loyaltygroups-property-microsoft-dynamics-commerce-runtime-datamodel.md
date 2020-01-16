---
title: LoyaltyCard.LoyaltyGroups Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyGroups Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.LoyaltyGroups
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycard.loyaltygroups(v=AX.60)
ms:contentKeyID: 62211251
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.LoyaltyGroups
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyGroups Property

Gets or sets the loyalty groups that the loyalty card belongs to.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyGroups As IList(Of LoyaltyGroup)
    Get
    Set
'Usage
Dim instance As LoyaltyCard
Dim value As IList(Of LoyaltyGroup)

value = instance.LoyaltyGroups

instance.LoyaltyGroups = value
```

``` csharp
[DataMemberAttribute]
public IList<LoyaltyGroup> LoyaltyGroups { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<LoyaltyGroup^>^ LoyaltyGroups {
    IList<LoyaltyGroup^>^ get ();
    void set (IList<LoyaltyGroup^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[LoyaltyGroup](loyaltygroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

