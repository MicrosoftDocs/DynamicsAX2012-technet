---
title: LoyaltyCardTransaction.EntryType Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: EntryType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyCardTransaction.EntryType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.loyaltycardtransaction.entrytype(v=AX.60)
ms:contentKeyID: 65315778
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyCardTransaction.EntryType
dev_langs:
- CSharp
- C++
- VB
---

# EntryType Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EntryType As LoyaltyRewardPointEntryType
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTransaction
Dim value As LoyaltyRewardPointEntryType

value = instance.EntryType
```

``` csharp
[DataMemberAttribute]
public LoyaltyRewardPointEntryType EntryType { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property LoyaltyRewardPointEntryType EntryType {
    LoyaltyRewardPointEntryType get ();
    internal: void set (LoyaltyRewardPointEntryType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyRewardPointEntryType](loyaltyrewardpointentrytype-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[LoyaltyCardTransaction Class](loyaltycardtransaction-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

