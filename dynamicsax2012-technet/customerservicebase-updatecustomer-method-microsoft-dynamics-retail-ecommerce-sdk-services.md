---
title: CustomerServiceBase.UpdateCustomer Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: UpdateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase.UpdateCustomer(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.customerservicebase.updatecustomer(v=AX.60)
ms:contentKeyID: 65317413
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase.UpdateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCustomer Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function UpdateCustomer ( _
    customer As Customer _
) As NullResponse
'Usage
Dim instance As CustomerServiceBase
Dim customer As Customer
Dim returnValue As NullResponse

returnValue = instance.UpdateCustomer(customer)
```

``` csharp
public virtual NullResponse UpdateCustomer(
    Customer customer
)
```

``` c++
public:
virtual NullResponse^ UpdateCustomer(
    Customer^ customer
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer](customer-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.NullResponse](nullresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[ICustomerService.UpdateCustomer(Customer)](icustomerservice-updatecustomer-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[CustomerServiceBase Class](customerservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

