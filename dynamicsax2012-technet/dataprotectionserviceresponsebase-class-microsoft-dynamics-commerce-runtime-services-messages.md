---
title: DataProtectionServiceResponseBase Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DataProtectionServiceResponseBase Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DataProtectionServiceResponseBase
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.dataprotectionserviceresponsebase(v=AX.60)
ms:contentKeyID: 65318856
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DataProtectionServiceResponseBase
dev_langs:
- CSharp
- C++
- VB
---

# DataProtectionServiceResponseBase Class

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class DataProtectionServiceResponseBase _
    Inherits Response
'Usage
Dim instance As DataProtectionServiceResponseBase
```

``` csharp
[DataContractAttribute]
public abstract class DataProtectionServiceResponseBase : Response
```

``` c++
[DataContractAttribute]
public ref class DataProtectionServiceResponseBase abstract : public Response
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DataProtectionServiceResponseBase  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DecryptDataServiceResponse](decryptdataserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.EncryptDataServiceResponse](encryptdataserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.HashDataServiceResponse](hashdataserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

