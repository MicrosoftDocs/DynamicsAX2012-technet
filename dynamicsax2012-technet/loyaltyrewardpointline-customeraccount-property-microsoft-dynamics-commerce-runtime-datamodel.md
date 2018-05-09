---
title: LoyaltyRewardPointLine.CustomerAccount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerAccount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.CustomerAccount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.customeraccount(v=AX.60)
ms:contentKeyID: 62210557
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.CustomerAccount
dev_langs:
- CSharp
- C++
- VB
---

# CustomerAccount Property

Gets or sets the customer account number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CUSTACCOUNT")> _
Public Property CustomerAccount As String
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As String

value = instance.CustomerAccount

instance.CustomerAccount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CUSTACCOUNT")]
public string CustomerAccount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CUSTACCOUNT")]
public:
property String^ CustomerAccount {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

