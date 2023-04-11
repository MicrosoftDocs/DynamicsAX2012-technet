---
title: CustomerController.SearchCustomers Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: SearchCustomers Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.SearchCustomers(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.customercontroller.searchcustomers(v=AX.60)
ms:contentKeyID: 65316606
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.SearchCustomers
dev_langs:
- CSharp
- C++
- VB
---

# SearchCustomers Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function SearchCustomers ( _
    emailAddress As String _
) As Boolean
'Usage
Dim instance As CustomerController
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

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

