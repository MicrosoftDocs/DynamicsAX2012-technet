---
title: ICustomerService.UpdateCustomer Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: UpdateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICustomerService.UpdateCustomer(Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.icustomerservice.updatecustomer(v=AX.60)
ms:contentKeyID: 62205812
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICustomerService.UpdateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function UpdateCustomer ( _
    customer As Customer _
) As NullResponse
'Usage
Dim instance As ICustomerService
Dim customer As Customer
Dim returnValue As NullResponse

returnValue = instance.UpdateCustomer(customer)
```

``` csharp
[OperationContractAttribute]
NullResponse UpdateCustomer(
    Customer customer
)
```

``` c++
[OperationContractAttribute]
NullResponse^ UpdateCustomer(
    Customer^ customer
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Customer](customer-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.NullResponse](nullresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Call success/failure response.  

## See Also

#### Reference

[ICustomerService Interface](icustomerservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

