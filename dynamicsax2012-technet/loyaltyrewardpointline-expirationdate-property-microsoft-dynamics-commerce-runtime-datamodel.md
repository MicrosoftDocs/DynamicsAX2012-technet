---
title: LoyaltyRewardPointLine.ExpirationDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExpirationDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.ExpirationDate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.expirationdate(v=AX.60)
ms:contentKeyID: 62208377
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.ExpirationDate
dev_langs:
- CSharp
- C++
- VB
---

# ExpirationDate Property

Gets or sets the expiration date of the earned reward points.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EXPIRATIONDATE")> _
Public Property ExpirationDate As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As Nullable(Of DateTimeOffset)

value = instance.ExpirationDate

instance.ExpirationDate = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EXPIRATIONDATE")]
public Nullable<DateTimeOffset> ExpirationDate { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EXPIRATIONDATE")]
public:
property Nullable<DateTimeOffset> ExpirationDate {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

