---
title: CustomerAffiliationsInfo.CustomerAffiliationItems Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: CustomerAffiliationItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.CustomerAffiliationsInfo.CustomerAffiliationItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.customeraffiliationsinfo.customeraffiliationitems(v=AX.60)
ms:contentKeyID: 62210086
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.CustomerAffiliationsInfo.CustomerAffiliationItems
dev_langs:
- CSharp
- C++
- VB
---

# CustomerAffiliationItems Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets Collection of affiliation elements.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property CustomerAffiliationItems As Collection(Of CustomerAffiliationInfo)
    Get
    Set
'Usage
Dim instance As CustomerAffiliationsInfo
Dim value As Collection(Of CustomerAffiliationInfo)

value = instance.CustomerAffiliationItems

instance.CustomerAffiliationItems = value
```

``` csharp
public Collection<CustomerAffiliationInfo> CustomerAffiliationItems { get; set; }
```

``` c++
public:
property Collection<CustomerAffiliationInfo^>^ CustomerAffiliationItems {
    Collection<CustomerAffiliationInfo^>^ get ();
    void set (Collection<CustomerAffiliationInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[CustomerAffiliationInfo](customeraffiliationinfo-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[CustomerAffiliationsInfo Class](customeraffiliationsinfo-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

