---
title: CustomerServiceBase.SearchCustomers Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SearchCustomers Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase.SearchCustomers(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.customerservicebase.searchcustomers(v=AX.60)
ms:contentKeyID: 65318332
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase.SearchCustomers
dev_langs:
- CSharp
- C++
- VB
---

# SearchCustomers Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function SearchCustomers ( _
    emailAddress As String _
) As Boolean
'Usage
Dim instance As CustomerServiceBase
Dim emailAddress As String
Dim returnValue As Boolean

returnValue = instance.SearchCustomers(emailAddress)
```

``` csharp
public virtual bool SearchCustomers(
    string emailAddress
)
```

``` c++
public:
virtual bool SearchCustomers(
    String^ emailAddress
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Implements

[ICustomerService.SearchCustomers(String)](icustomerservice-searchcustomers-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[CustomerServiceBase Class](customerservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

