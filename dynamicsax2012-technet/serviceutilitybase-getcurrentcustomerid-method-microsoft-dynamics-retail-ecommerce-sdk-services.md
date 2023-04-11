---
title: ServiceUtilityBase.GetCurrentCustomerId Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetCurrentCustomerId Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceUtilityBase.GetCurrentCustomerId(System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.serviceutilitybase.getcurrentcustomerid(v=AX.60)
ms:contentKeyID: 65318514
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceUtilityBase.GetCurrentCustomerId
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrentCustomerId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public MustOverride Function GetCurrentCustomerId ( _
    isMandatory As Boolean _
) As String
'Usage
Dim instance As ServiceUtilityBase
Dim isMandatory As Boolean
Dim returnValue As String

returnValue = instance.GetCurrentCustomerId(isMandatory)
```

``` csharp
public abstract string GetCurrentCustomerId(
    bool isMandatory
)
```

``` c++
public:
virtual String^ GetCurrentCustomerId(
    bool isMandatory
) abstract
```

#### Parameters

  - isMandatory  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ServiceUtilityBase Class](serviceutilitybase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

