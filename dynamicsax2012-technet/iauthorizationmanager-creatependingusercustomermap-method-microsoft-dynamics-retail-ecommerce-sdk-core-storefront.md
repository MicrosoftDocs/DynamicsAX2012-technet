---
title: IAuthorizationManager.CreatePendingUserCustomerMap Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront)
TOCTitle: CreatePendingUserCustomerMap Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront.IAuthorizationManager.CreatePendingUserCustomerMap(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.storefront.iauthorizationmanager.creatependingusercustomermap(v=AX.60)
ms:contentKeyID: 65316547
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront.IAuthorizationManager.CreatePendingUserCustomerMap
dev_langs:
- CSharp
- C++
- VB
---

# CreatePendingUserCustomerMap Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront](microsoft-dynamics-retail-ecommerce-sdk-core-storefront-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Function CreatePendingUserCustomerMap ( _
    userId As String, _
    customerId As String, _
    xmlData As String _
) As UserCustomerMap
'Usage
Dim instance As IAuthorizationManager
Dim userId As String
Dim customerId As String
Dim xmlData As String
Dim returnValue As UserCustomerMap

returnValue = instance.CreatePendingUserCustomerMap(userId, _
    customerId, xmlData)
```

``` csharp
UserCustomerMap CreatePendingUserCustomerMap(
    string userId,
    string customerId,
    string xmlData
)
```

``` c++
UserCustomerMap^ CreatePendingUserCustomerMap(
    String^ userId, 
    String^ customerId, 
    String^ xmlData
)
```

#### Parameters

  - userId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - xmlData  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.UserCustomerMap](usercustomermap-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[IAuthorizationManager Interface](iauthorizationmanager-interface-microsoft-dynamics-retail-ecommerce-sdk-core-storefront.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-storefront-namespace.md)

