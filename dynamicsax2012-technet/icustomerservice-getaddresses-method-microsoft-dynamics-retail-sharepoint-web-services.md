---
title: ICustomerService.GetAddresses Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetAddresses Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICustomerService.GetAddresses
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.icustomerservice.getaddresses(v=AX.60)
ms:contentKeyID: 62203564
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICustomerService.GetAddresses
dev_langs:
- CSharp
- C++
- VB
---

# GetAddresses Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the addresses.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetAddresses As AddressCollectionResponse
'Usage
Dim instance As ICustomerService
Dim returnValue As AddressCollectionResponse

returnValue = instance.GetAddresses()
```

``` csharp
[OperationContractAttribute]
AddressCollectionResponse GetAddresses()
```

``` c++
[OperationContractAttribute]
AddressCollectionResponse^ GetAddresses()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.AddressCollectionResponse](addresscollectionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
An address collection response.  

## See Also

#### Reference

[ICustomerService Interface](icustomerservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

