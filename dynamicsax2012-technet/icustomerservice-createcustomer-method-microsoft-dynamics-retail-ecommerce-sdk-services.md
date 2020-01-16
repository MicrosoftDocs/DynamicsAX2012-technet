---
title: ICustomerService.CreateCustomer Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: CreateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICustomerService.CreateCustomer(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.icustomerservice.createcustomer(v=AX.60)
ms:contentKeyID: 65315633
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICustomerService.CreateCustomer
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
<OperationContractAttribute> _
Function CreateCustomer ( _
    customer As Customer _
) As CustomerResponse
'Usage
Dim instance As ICustomerService
Dim customer As Customer
Dim returnValue As CustomerResponse

returnValue = instance.CreateCustomer(customer)
```

``` csharp
[OperationContractAttribute]
CustomerResponse CreateCustomer(
    Customer customer
)
```

``` c++
[OperationContractAttribute]
CustomerResponse^ CreateCustomer(
    Customer^ customer
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer](customer-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerResponse](customerresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ICustomerService Interface](icustomerservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

