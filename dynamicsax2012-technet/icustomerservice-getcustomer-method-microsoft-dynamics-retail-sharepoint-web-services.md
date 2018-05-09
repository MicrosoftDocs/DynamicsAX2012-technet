---
title: ICustomerService.GetCustomer Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICustomerService.GetCustomer
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.icustomerservice.getcustomer(v=AX.60)
ms:contentKeyID: 62205809
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICustomerService.GetCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomer Method

Gets the customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetCustomer As CustomerResponse
'Usage
Dim instance As ICustomerService
Dim returnValue As CustomerResponse

returnValue = instance.GetCustomer()
```

``` csharp
[OperationContractAttribute]
CustomerResponse GetCustomer()
```

``` c++
[OperationContractAttribute]
CustomerResponse^ GetCustomer()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CustomerResponse](customerresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A customer response.  

## See Also

#### Reference

[ICustomerService Interface](icustomerservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

