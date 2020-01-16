---
title: AffiliationInfo.AffiliationRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: AffiliationRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.AffiliationInfo.AffiliationRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.affiliationinfo.affiliationrecordid(v=AX.60)
ms:contentKeyID: 62212922
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.AffiliationInfo.AffiliationRecordId
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationRecordId Property

Gets or sets the record identifier of the affiliation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property AffiliationRecordId As Long
    Get
    Set
'Usage
Dim instance As AffiliationInfo
Dim value As Long

value = instance.AffiliationRecordId

instance.AffiliationRecordId = value
```

``` csharp
public long AffiliationRecordId { get; set; }
```

``` c++
public:
property long long AffiliationRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[AffiliationInfo Class](affiliationinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

