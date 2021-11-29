---
title: GetChargesServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetChargesServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChargesServiceRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getchargesservicerequest(v=AX.60)
ms:contentKeyID: 62211641
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChargesServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# GetChargesServiceRequest Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Request to populate the auto-charges, price charges, and shipping charges on a transaction and its lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public NotInheritable Class GetChargesServiceRequest _
    Inherits ServiceRequest
'Usage
Dim instance As GetChargesServiceRequest
```

``` csharp
[DataContractAttribute]
public sealed class GetChargesServiceRequest : ServiceRequest
```

``` c++
[DataContractAttribute]
public ref class GetChargesServiceRequest sealed : public ServiceRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest](servicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChargesServiceRequest  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

