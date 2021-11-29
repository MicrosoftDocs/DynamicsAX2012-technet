---
title: CustomerDataManager.ProcessCustomerImages Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ProcessCustomerImages Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.ProcessCustomerImages(System.Collections.Generic.ICollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.processcustomerimages(v=AX.60)
ms:contentKeyID: 65322560
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.ProcessCustomerImages
dev_langs:
- CSharp
- C++
- VB
---

# ProcessCustomerImages Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub ProcessCustomerImages ( _
    customers As ICollection(Of Customer) _
)
'Usage
Dim instance As CustomerDataManager
Dim customers As ICollection(Of Customer)

instance.ProcessCustomerImages(customers)
```

``` csharp
public void ProcessCustomerImages(
    ICollection<Customer> customers
)
```

``` c++
public:
void ProcessCustomerImages(
    ICollection<Customer^>^ customers
)
```

#### Parameters

  - customers  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

