---
title: ServiceResponse.Errors Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: Errors Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse.Errors
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.serviceresponse.errors(v=AX.60)
ms:contentKeyID: 65315753
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse.Errors
dev_langs:
- CSharp
- C++
- VB
---

# Errors Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Errors As List(Of ResponseError)
    Get
    Private Set
'Usage
Dim instance As ServiceResponse
Dim value As List(Of ResponseError)

value = instance.Errors
```

``` csharp
[DataMemberAttribute]
public List<ResponseError> Errors { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property List<ResponseError^>^ Errors {
    List<ResponseError^>^ get ();
    private: void set (List<ResponseError^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[ResponseError](responseerror-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)\>  

## See Also

#### Reference

[ServiceResponse Class](serviceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

