---
title: DataProtectionRequestHandler.HashData Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: HashData Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.DataProtectionRequestHandler.HashData(Microsoft.Dynamics.Commerce.Runtime.Messages.HashDataServiceRequest)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.dataprotectionrequesthandler.hashdata(v=AX.60)
ms:contentKeyID: 65317567
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.DataProtectionRequestHandler.HashData
dev_langs:
- CSharp
- C++
- VB
---

# HashData Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone (in Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone.dll)

## Syntax

``` vb
'Declaration
Public Shared Function HashData ( _
    request As HashDataServiceRequest _
) As HashDataServiceResponse
'Usage
Dim request As HashDataServiceRequest
Dim returnValue As HashDataServiceResponse

returnValue = DataProtectionRequestHandler.HashData(request)
```

``` csharp
public static HashDataServiceResponse HashData(
    HashDataServiceRequest request
)
```

``` c++
public:
static HashDataServiceResponse^ HashData(
    HashDataServiceRequest^ request
)
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.HashDataServiceRequest](hashdataservicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.HashDataServiceResponse](hashdataserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)  

## See Also

#### Reference

[DataProtectionRequestHandler Class](dataprotectionrequesthandler-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

