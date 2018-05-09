---
title: CustomerServiceBase.CreateCustomer Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: CreateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase.CreateCustomer(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.customerservicebase.createcustomer(v=AX.60)
ms:contentKeyID: 65316755
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase.CreateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# CreateCustomer Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function CreateCustomer ( _
    customer As Customer _
) As CustomerResponse
'Usage
Dim instance As CustomerServiceBase
Dim customer As Customer
Dim returnValue As CustomerResponse

returnValue = instance.CreateCustomer(customer)
```

``` csharp
public virtual CustomerResponse CreateCustomer(
    Customer customer
)
```

``` c++
public:
virtual CustomerResponse^ CreateCustomer(
    Customer^ customer
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer](customer-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerResponse](customerresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[ICustomerService.CreateCustomer(Customer)](icustomerservice-createcustomer-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[CustomerServiceBase Class](customerservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

