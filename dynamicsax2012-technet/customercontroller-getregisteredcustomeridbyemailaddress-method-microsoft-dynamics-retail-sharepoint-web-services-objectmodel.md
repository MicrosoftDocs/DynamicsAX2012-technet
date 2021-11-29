---
title: CustomerController.GetRegisteredCustomerIdByEmailAddress Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: GetRegisteredCustomerIdByEmailAddress Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.CustomerController.GetRegisteredCustomerIdByEmailAddress(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.customercontroller.getregisteredcustomeridbyemailaddress(v=AX.60)
ms:contentKeyID: 62205402
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.CustomerController.GetRegisteredCustomerIdByEmailAddress
dev_langs:
- CSharp
- C++
- VB
---

# GetRegisteredCustomerIdByEmailAddress Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer account number using the specified e-mail address.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetRegisteredCustomerIdByEmailAddress ( _
    emailAddress As String _
) As String
'Usage
Dim emailAddress As String
Dim returnValue As String

returnValue = CustomerController.GetRegisteredCustomerIdByEmailAddress(emailAddress)
```

``` csharp
public static string GetRegisteredCustomerIdByEmailAddress(
    string emailAddress
)
```

``` c++
public:
static String^ GetRegisteredCustomerIdByEmailAddress(
    String^ emailAddress
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The customer identifier.  

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)

