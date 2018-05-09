---
title: CustomerDataManager.CreateOrUpdateCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CreateOrUpdateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.CreateOrUpdateCustomer(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.createorupdatecustomer(v=AX.60)
ms:contentKeyID: 62208435
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.CreateOrUpdateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# CreateOrUpdateCustomer Method

Creates or updates a customer address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function CreateOrUpdateCustomer ( _
    customer As Customer _
) As Customer
'Usage
Dim instance As CustomerDataManager
Dim customer As Customer
Dim returnValue As Customer

returnValue = instance.CreateOrUpdateCustomer(customer)
```

``` csharp
public Customer CreateOrUpdateCustomer(
    Customer customer
)
```

``` c++
public:
Customer^ CreateOrUpdateCustomer(
    Customer^ customer
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Updated customer.  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

