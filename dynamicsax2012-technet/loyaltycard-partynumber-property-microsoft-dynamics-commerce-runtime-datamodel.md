---
title: LoyaltyCard.PartyNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PartyNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.PartyNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycard.partynumber(v=AX.60)
ms:contentKeyID: 62214901
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.PartyNumber
dev_langs:
- CSharp
- C++
- VB
---

# PartyNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the party number of the card owner.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("PARTYNUMBER")> _
Public Property PartyNumber As String
    Get
    Set
'Usage
Dim instance As LoyaltyCard
Dim value As String

value = instance.PartyNumber

instance.PartyNumber = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("PARTYNUMBER")]
public string PartyNumber { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"PARTYNUMBER")]
public:
property String^ PartyNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

