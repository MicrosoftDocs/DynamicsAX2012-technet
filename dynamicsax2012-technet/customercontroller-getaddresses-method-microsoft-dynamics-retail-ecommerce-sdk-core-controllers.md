---
title: CustomerController.GetAddresses Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetAddresses Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.GetAddresses(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.customercontroller.getaddresses(v=AX.60)
ms:contentKeyID: 65315786
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.GetAddresses
dev_langs:
- CSharp
- C++
- VB
---

# GetAddresses Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetAddresses ( _
    accountNumber As String _
) As Collection(Of Address)
'Usage
Dim instance As CustomerController
Dim accountNumber As String
Dim returnValue As Collection(Of Address)

returnValue = instance.GetAddresses(accountNumber)
```

``` csharp
public virtual Collection<Address> GetAddresses(
    string accountNumber
)
```

``` c++
public:
virtual Collection<Address^>^ GetAddresses(
    String^ accountNumber
)
```

#### Parameters

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[Address](address-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

