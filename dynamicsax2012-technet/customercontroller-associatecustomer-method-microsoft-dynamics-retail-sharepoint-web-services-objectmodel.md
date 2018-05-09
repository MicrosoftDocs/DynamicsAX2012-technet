---
title: CustomerController.AssociateCustomer Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: AssociateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.CustomerController.AssociateCustomer(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.customercontroller.associatecustomer(v=AX.60)
ms:contentKeyID: 62207538
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.CustomerController.AssociateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# AssociateCustomer Method

Associate an existing customer to the current credentials if the criteria matches.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub AssociateCustomer ( _
    email As String _
)
'Usage
Dim email As String

CustomerController.AssociateCustomer(email)
```

``` csharp
public static void AssociateCustomer(
    string email
)
```

``` c++
public:
static void AssociateCustomer(
    String^ email
)
```

#### Parameters

  - email  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>DataValidationException</td>
<td><p>Thrown when the customer cannot be found.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)

