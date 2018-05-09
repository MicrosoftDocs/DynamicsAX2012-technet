---
title: DataModelExtensions.MergeDatabaseCustomerIntoInputCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MergeDatabaseCustomerIntoInputCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.DataModelExtensions.MergeDatabaseCustomerIntoInputCustomer(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer,Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.datamodelextensions.mergedatabasecustomerintoinputcustomer(v=AX.60)
ms:contentKeyID: 62209859
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DataModelExtensions.MergeDatabaseCustomerIntoInputCustomer
dev_langs:
- CSharp
- C++
- VB
---

# MergeDatabaseCustomerIntoInputCustomer Method

Adapt and merge local changes to a Customer object with the saved copy in preparation for saving to AX and CRT.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function MergeDatabaseCustomerIntoInputCustomer ( _
    inputCustomer As Customer, _
    databaseCustomer As Customer _
) As Customer
'Usage
Dim inputCustomer As Customer
Dim databaseCustomer As Customer
Dim returnValue As Customer

returnValue = DataModelExtensions.MergeDatabaseCustomerIntoInputCustomer(inputCustomer, _
    databaseCustomer)
```

``` csharp
public static Customer MergeDatabaseCustomerIntoInputCustomer(
    Customer inputCustomer,
    Customer databaseCustomer
)
```

``` c++
public:
static Customer^ MergeDatabaseCustomerIntoInputCustomer(
    Customer^ inputCustomer, 
    Customer^ databaseCustomer
)
```

#### Parameters

  - inputCustomer  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - databaseCustomer  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The customer data.  

## See Also

#### Reference

[DataModelExtensions Class](datamodelextensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

