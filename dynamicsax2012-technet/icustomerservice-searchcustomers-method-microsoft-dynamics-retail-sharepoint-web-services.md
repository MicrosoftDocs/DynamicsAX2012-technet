---
title: ICustomerService.SearchCustomers Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: SearchCustomers Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICustomerService.SearchCustomers(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.icustomerservice.searchcustomers(v=AX.60)
ms:contentKeyID: 62204658
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICustomerService.SearchCustomers
dev_langs:
- CSharp
- C++
- VB
---

# SearchCustomers Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Search for a customer given the corresponding email address.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function SearchCustomers ( _
    emailAddress As String _
) As Boolean
'Usage
Dim instance As ICustomerService
Dim emailAddress As String
Dim returnValue As Boolean

returnValue = instance.SearchCustomers(emailAddress)
```

``` csharp
[OperationContractAttribute]
bool SearchCustomers(
    string emailAddress
)
```

``` c++
[OperationContractAttribute]
bool SearchCustomers(
    String^ emailAddress
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the customer exists, false otherwise.  

## See Also

#### Reference

[ICustomerService Interface](icustomerservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

