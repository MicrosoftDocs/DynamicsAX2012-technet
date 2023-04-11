---
title: CustomerOrderInfo.Affiliations Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: Affiliations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.Affiliations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.affiliations(v=AX.60)
ms:contentKeyID: 62209124
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.Affiliations
dev_langs:
- CSharp
- C++
- VB
---

# Affiliations Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the affiliation information collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property Affiliations As Collection(Of AffiliationInfo)
    Get
    Private Set
'Usage
Dim instance As CustomerOrderInfo
Dim value As Collection(Of AffiliationInfo)

value = instance.Affiliations
```

``` csharp
public Collection<AffiliationInfo> Affiliations { get; private set; }
```

``` c++
public:
property Collection<AffiliationInfo^>^ Affiliations {
    Collection<AffiliationInfo^>^ get ();
    private: void set (Collection<AffiliationInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[AffiliationInfo](affiliationinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[CustomerOrderInfo Class](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

