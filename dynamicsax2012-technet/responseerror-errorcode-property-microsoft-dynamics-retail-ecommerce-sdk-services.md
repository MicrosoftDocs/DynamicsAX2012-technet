---
title: ResponseError.ErrorCode Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ErrorCode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ResponseError.ErrorCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.responseerror.errorcode(v=AX.60)
ms:contentKeyID: 65318004
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ResponseError.ErrorCode
dev_langs:
- CSharp
- C++
- VB
---

# ErrorCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ErrorCode As String
    Get
    Set
'Usage
Dim instance As ResponseError
Dim value As String

value = instance.ErrorCode

instance.ErrorCode = value
```

``` csharp
[DataMemberAttribute]
public string ErrorCode { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ErrorCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ResponseError Class](responseerror-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

