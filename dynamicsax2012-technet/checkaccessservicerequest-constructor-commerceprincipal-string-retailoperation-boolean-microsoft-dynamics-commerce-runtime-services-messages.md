---
title: CheckAccessServiceRequest Constructor (CommercePrincipal, String , RetailOperation, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CheckAccessServiceRequest Constructor (CommercePrincipal, String , RetailOperation, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal,System.String[],Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.checkaccessservicerequest.checkaccessservicerequest(v=AX.60)
ms:contentKeyID: 65319835
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CheckAccessServiceRequest Constructor (CommercePrincipal, String , RetailOperation, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    commercePrincipal As CommercePrincipal, _
    allowedRoles As String(), _
    operationId As RetailOperation, _
    deviceTokenRequired As Boolean _
)
'Usage
Dim commercePrincipal As CommercePrincipal
Dim allowedRoles As String()
Dim operationId As RetailOperation
Dim deviceTokenRequired As Boolean

Dim instance As New CheckAccessServiceRequest(commercePrincipal, _
    allowedRoles, operationId, deviceTokenRequired)
```

``` csharp
public CheckAccessServiceRequest(
    CommercePrincipal commercePrincipal,
    string[] allowedRoles,
    RetailOperation operationId,
    bool deviceTokenRequired
)
```

``` c++
public:
CheckAccessServiceRequest(
    CommercePrincipal^ commercePrincipal, 
    array<String^>^ allowedRoles, 
    RetailOperation operationId, 
    bool deviceTokenRequired
)
```

#### Parameters

  - commercePrincipal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - allowedRoles  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

<!-- end list -->

  - operationId  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - deviceTokenRequired  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[CheckAccessServiceRequest Class](checkaccessservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[CheckAccessServiceRequest Overload](checkaccessservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

