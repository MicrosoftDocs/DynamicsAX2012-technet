---
title: LoyaltyRewardPointLine.EntryTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EntryTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.EntryTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.entrytypevalue(v=AX.60)
ms:contentKeyID: 62210631
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.EntryTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# EntryTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the EntryType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EntryTypeValue As Integer
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As Integer

value = instance.EntryTypeValue

instance.EntryTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int EntryTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int EntryTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

