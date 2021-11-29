---
title: LoyaltyCard.CustomerAccount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerAccount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.CustomerAccount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycard.customeraccount(v=AX.60)
ms:contentKeyID: 62208183
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.CustomerAccount
dev_langs:
- CSharp
- C++
- VB
---

# CustomerAccount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer account number of loyalty card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CUSTOMERACCOUNT")> _
<DataMemberAttribute> _
Public Property CustomerAccount As String
    Get
    Set
'Usage
Dim instance As LoyaltyCard
Dim value As String

value = instance.CustomerAccount

instance.CustomerAccount = value
```

``` csharp
[ColumnAttribute("CUSTOMERACCOUNT")]
[DataMemberAttribute]
public string CustomerAccount { get; set; }
```

``` c++
[ColumnAttribute(L"CUSTOMERACCOUNT")]
[DataMemberAttribute]
public:
property String^ CustomerAccount {
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

