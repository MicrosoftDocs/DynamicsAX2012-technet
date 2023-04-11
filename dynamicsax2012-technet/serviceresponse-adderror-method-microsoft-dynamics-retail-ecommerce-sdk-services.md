---
title: ServiceResponse.AddError Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: AddError Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse.AddError(System.String,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.serviceresponse.adderror(v=AX.60)
ms:contentKeyID: 65317753
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse.AddError
dev_langs:
- CSharp
- C++
- VB
---

# AddError Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub AddError ( _
    errorCode As String, _
    errorMessage As String, _
    ParamArray args As Object() _
)
'Usage
Dim instance As ServiceResponse
Dim errorCode As String
Dim errorMessage As String
Dim args As Object()

instance.AddError(errorCode, errorMessage, _
    args)
```

``` csharp
public void AddError(
    string errorCode,
    string errorMessage,
    params Object[] args
)
```

``` c++
public:
void AddError(
    String^ errorCode, 
    String^ errorMessage, 
    ... array<Object^>^ args
)
```

#### Parameters

  - errorCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - errorMessage  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - args  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[ServiceResponse Class](serviceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

