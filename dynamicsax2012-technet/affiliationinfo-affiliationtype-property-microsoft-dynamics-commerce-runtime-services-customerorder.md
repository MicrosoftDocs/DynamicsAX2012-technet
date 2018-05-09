---
title: AffiliationInfo.AffiliationType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: AffiliationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.AffiliationInfo.AffiliationType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.customerorder.affiliationinfo.affiliationtype(v=AX.60)
ms:contentKeyID: 62213899
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.AffiliationInfo.AffiliationType
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationType Property

Gets or sets the affiliation type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property AffiliationType As RetailAffiliationType
    Get
    Set
'Usage
Dim instance As AffiliationInfo
Dim value As RetailAffiliationType

value = instance.AffiliationType

instance.AffiliationType = value
```

``` csharp
public RetailAffiliationType AffiliationType { get; set; }
```

``` c++
public:
property RetailAffiliationType AffiliationType {
    RetailAffiliationType get ();
    void set (RetailAffiliationType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailAffiliationType](retailaffiliationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [RetailAffiliationType](retailaffiliationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[AffiliationInfo Class](affiliationinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

