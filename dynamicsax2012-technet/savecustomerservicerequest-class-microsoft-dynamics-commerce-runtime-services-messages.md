---
title: SaveCustomerServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SaveCustomerServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerServiceRequest
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.savecustomerservicerequest(v=AX.60)
ms:contentKeyID: 49847804
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# SaveCustomerServiceRequest Class

SaveCustomerServiceRequest class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
<KnownTypeAttribute(GetType(Address))> _
Public NotInheritable Class SaveCustomerServiceRequest _
    Inherits ServiceRequest
'Usage
Dim instance As SaveCustomerServiceRequest
```

``` csharp
[DataContractAttribute]
[KnownTypeAttribute(typeof(Address))]
public sealed class SaveCustomerServiceRequest : ServiceRequest
```

``` c++
[DataContractAttribute]
[KnownTypeAttribute(typeof(Address))]
public ref class SaveCustomerServiceRequest sealed : public ServiceRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest](servicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerServiceRequest  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

