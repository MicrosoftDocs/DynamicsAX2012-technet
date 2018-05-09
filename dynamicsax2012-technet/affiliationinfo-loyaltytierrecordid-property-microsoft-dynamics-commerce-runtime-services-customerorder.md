---
title: AffiliationInfo.LoyaltyTierRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: LoyaltyTierRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.AffiliationInfo.LoyaltyTierRecordId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.customerorder.affiliationinfo.loyaltytierrecordid(v=AX.60)
ms:contentKeyID: 62210753
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.AffiliationInfo.LoyaltyTierRecordId
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyTierRecordId Property

Gets or sets the record identifier of the loyalty tier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property LoyaltyTierRecordId As Long
    Get
    Set
'Usage
Dim instance As AffiliationInfo
Dim value As Long

value = instance.LoyaltyTierRecordId

instance.LoyaltyTierRecordId = value
```

``` csharp
public long LoyaltyTierRecordId { get; set; }
```

``` c++
public:
property long long LoyaltyTierRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[AffiliationInfo Class](affiliationinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

