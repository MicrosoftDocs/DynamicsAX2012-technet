---
title: LoyaltyCard.CustomerDataAreaId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerDataAreaId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.CustomerDataAreaId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycard.customerdataareaid(v=AX.60)
ms:contentKeyID: 62207874
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.CustomerDataAreaId
dev_langs:
- CSharp
- C++
- VB
---

# CustomerDataAreaId Property

Gets or sets the data area identifier of the customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CUSTOMERDATAAREAID")> _
Public Property CustomerDataAreaId As String
    Get
    Set
'Usage
Dim instance As LoyaltyCard
Dim value As String

value = instance.CustomerDataAreaId

instance.CustomerDataAreaId = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CUSTOMERDATAAREAID")]
public string CustomerDataAreaId { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CUSTOMERDATAAREAID")]
public:
property String^ CustomerDataAreaId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

