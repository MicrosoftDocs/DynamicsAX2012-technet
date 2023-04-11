---
title: DataProtectionServiceRequestBase Class (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DataProtectionServiceRequestBase Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Messages.DataProtectionServiceRequestBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.dataprotectionservicerequestbase(v=AX.60)
ms:contentKeyID: 65321101
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DataProtectionServiceRequestBase
dev_langs:
- CSharp
- C++
- VB
---

# DataProtectionServiceRequestBase Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class DataProtectionServiceRequestBase _
    Inherits ServiceRequest
'Usage
Dim instance As DataProtectionServiceRequestBase
```

``` csharp
[DataContractAttribute]
public abstract class DataProtectionServiceRequestBase : ServiceRequest
```

``` c++
[DataContractAttribute]
public ref class DataProtectionServiceRequestBase abstract : public ServiceRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest](servicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.Messages.DataProtectionServiceRequestBase  
        [Microsoft.Dynamics.Commerce.Runtime.Messages.DecryptDataServiceRequest](decryptdataservicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Messages.EncryptDataServiceRequest](encryptdataservicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Messages.HashDataServiceRequest](hashdataservicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

