---
title: CheckAccessServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CheckAccessServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.checkaccessservicerequest(v=AX.60)
ms:contentKeyID: 62209318
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# CheckAccessServiceRequest Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Service request for user authentication.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class CheckAccessServiceRequest _
    Inherits ServiceRequest
'Usage
Dim instance As CheckAccessServiceRequest
```

``` csharp
[DataContractAttribute]
public class CheckAccessServiceRequest : ServiceRequest
```

``` c++
[DataContractAttribute]
public ref class CheckAccessServiceRequest : public ServiceRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest](servicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessHasShiftServiceRequest](checkaccesshasshiftservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessIsManagerServiceRequest](checkaccessismanagerservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

