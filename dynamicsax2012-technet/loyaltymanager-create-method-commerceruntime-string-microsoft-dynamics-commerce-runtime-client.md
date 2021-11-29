---
title: LoyaltyManager.Create Method (CommerceRuntime, String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: Create Method (CommerceRuntime, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager.Create(Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.loyaltymanager.create(v=AX.60)
ms:contentKeyID: 62211285
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Create Method (CommerceRuntime, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a new instance of the [LoyaltyManager](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Create ( _
    runtime As CommerceRuntime, _
    locale As String _
) As LoyaltyManager
'Usage
Dim runtime As CommerceRuntime
Dim locale As String
Dim returnValue As LoyaltyManager

returnValue = LoyaltyManager.Create(runtime, _
    locale)
```

``` csharp
public static LoyaltyManager Create(
    CommerceRuntime runtime,
    string locale
)
```

``` c++
public:
static LoyaltyManager^ Create(
    CommerceRuntime^ runtime, 
    String^ locale
)
```

#### Parameters

  - runtime  
    Type: [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - locale  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md)  
A new instance of [LoyaltyManager](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md) class.  

## See Also

#### Reference

[LoyaltyManager Class](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Create Overload](loyaltymanager-create-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

