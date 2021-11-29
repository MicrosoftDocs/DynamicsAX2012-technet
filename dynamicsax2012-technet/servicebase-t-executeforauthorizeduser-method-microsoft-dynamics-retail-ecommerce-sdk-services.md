---
title: ServiceBase(T).ExecuteForAuthorizedUser Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ExecuteForAuthorizedUser Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1.ExecuteForAuthorizedUser(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse,System.Action{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/Dn988288(v=AX.60)
ms:contentKeyID: 65317333
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1.ExecuteForAuthorizedUser
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteForAuthorizedUser Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Protected MustOverride Sub ExecuteForAuthorizedUser ( _
    response As ServiceResponse, _
    action As Action(Of String) _
)
'Usage
Dim response As ServiceResponse
Dim action As Action(Of String)

Me.ExecuteForAuthorizedUser(response, _
    action)
```

``` csharp
protected abstract void ExecuteForAuthorizedUser(
    ServiceResponse response,
    Action<string> action
)
```

``` c++
protected:
virtual void ExecuteForAuthorizedUser(
    ServiceResponse^ response, 
    Action<String^>^ action
) abstract
```

#### Parameters

  - response  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

<!-- end list -->

  - action  
    Type: [System.Action](https://technet.microsoft.com/library/018hxwa8\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[ServiceBase\<T\> Class](servicebase-t-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

