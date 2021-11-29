---
title: CheckAccessRequest Constructor (CommercePrincipal, RetailOperation) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CheckAccessRequest Constructor (CommercePrincipal, RetailOperation)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.CheckAccessRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal,Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.checkaccessrequest.checkaccessrequest(v=AX.60)
ms:contentKeyID: 62212270
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CheckAccessRequest Constructor (CommercePrincipal, RetailOperation)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [CheckAccessRequest](checkaccessrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    commercePrincipal As CommercePrincipal, _
    retailOperation As RetailOperation _
)
'Usage
Dim commercePrincipal As CommercePrincipal
Dim retailOperation As RetailOperation

Dim instance As New CheckAccessRequest(commercePrincipal, _
    retailOperation)
```

``` csharp
public CheckAccessRequest(
    CommercePrincipal commercePrincipal,
    RetailOperation retailOperation
)
```

``` c++
public:
CheckAccessRequest(
    CommercePrincipal^ commercePrincipal, 
    RetailOperation retailOperation
)
```

#### Parameters

  - commercePrincipal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - retailOperation  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CheckAccessRequest Class](checkaccessrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[CheckAccessRequest Overload](checkaccessrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

