---
title: LoyaltyRewardPointLine.EntryTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EntryTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.EntryTime
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.entrytime(v=AX.60)
ms:contentKeyID: 62208206
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.EntryTime
dev_langs:
- CSharp
- C++
- VB
---

# EntryTime Property

Gets or sets the entry time of the reward points.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ENTRYTIME")> _
<DataMemberAttribute> _
Public Property EntryTime As Integer
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As Integer

value = instance.EntryTime

instance.EntryTime = value
```

``` csharp
[ColumnAttribute("ENTRYTIME")]
[DataMemberAttribute]
public int EntryTime { get; set; }
```

``` c++
[ColumnAttribute(L"ENTRYTIME")]
[DataMemberAttribute]
public:
property int EntryTime {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

