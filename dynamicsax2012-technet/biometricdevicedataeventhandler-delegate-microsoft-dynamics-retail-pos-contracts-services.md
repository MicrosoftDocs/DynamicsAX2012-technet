---
title: BiometricDeviceDataEventHandler Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: BiometricDeviceDataEventHandler Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.BiometricDeviceDataEventHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.biometricdevicedataeventhandler(v=AX.60)
ms:contentKeyID: 49834864
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.BiometricDeviceDataEventHandler
dev_langs:
- CSharp
- C++
- VB
---

# BiometricDeviceDataEventHandler Delegate


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Biometric device data event delegate.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub BiometricDeviceDataEventHandler ( _
    key As String, _
    template As Byte() _
)
'Usage
Dim instance As New BiometricDeviceDataEventHandler(AddressOf HandlerMethod)
```

``` csharp
public delegate void BiometricDeviceDataEventHandler(
    string key,
    byte[] template
)
```

``` c++
public delegate void BiometricDeviceDataEventHandler(
    String^ key, 
    array<unsigned char>^ template
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - template  
    Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

