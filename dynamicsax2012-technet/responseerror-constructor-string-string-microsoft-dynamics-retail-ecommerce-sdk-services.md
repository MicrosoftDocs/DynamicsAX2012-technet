---
title: ResponseError Constructor (String, String) (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ResponseError Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ResponseError.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.responseerror.responseerror(v=AX.60)
ms:contentKeyID: 65317286
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ResponseError Constructor (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorCode As String, _
    errorMessage As String _
)
'Usage
Dim errorCode As String
Dim errorMessage As String

Dim instance As New ResponseError(errorCode, _
    errorMessage)
```

``` csharp
public ResponseError(
    string errorCode,
    string errorMessage
)
```

``` c++
public:
ResponseError(
    String^ errorCode, 
    String^ errorMessage
)
```

#### Parameters

  - errorCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - errorMessage  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ResponseError Class](responseerror-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[ResponseError Overload](responseerror-constructor-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

