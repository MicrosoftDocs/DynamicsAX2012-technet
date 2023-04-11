---
title: CustomerController.UpdateAddresses Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: UpdateAddresses Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.UpdateAddresses(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Address})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.customercontroller.updateaddresses(v=AX.60)
ms:contentKeyID: 65318024
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.UpdateAddresses
dev_langs:
- CSharp
- C++
- VB
---

# UpdateAddresses Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Sub UpdateAddresses ( _
    accountNumber As String, _
    updatedAddresses As IEnumerable(Of Address) _
)
'Usage
Dim instance As CustomerController
Dim accountNumber As String
Dim updatedAddresses As IEnumerable(Of Address)

instance.UpdateAddresses(accountNumber, _
    updatedAddresses)
```

``` csharp
public virtual void UpdateAddresses(
    string accountNumber,
    IEnumerable<Address> updatedAddresses
)
```

``` c++
public:
virtual void UpdateAddresses(
    String^ accountNumber, 
    IEnumerable<Address^>^ updatedAddresses
)
```

#### Parameters

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - updatedAddresses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Address](address-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

