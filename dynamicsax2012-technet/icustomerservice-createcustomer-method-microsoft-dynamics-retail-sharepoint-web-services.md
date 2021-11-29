---
title: ICustomerService.CreateCustomer Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: CreateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICustomerService.CreateCustomer(Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.icustomerservice.createcustomer(v=AX.60)
ms:contentKeyID: 62206200
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICustomerService.CreateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# CreateCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates the customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

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
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer](customer-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CustomerResponse](customerresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A customer response.  

## See Also

#### Reference

[ICustomerService Interface](icustomerservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

