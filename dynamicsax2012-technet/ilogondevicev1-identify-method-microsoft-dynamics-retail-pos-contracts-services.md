---
title: ILogOnDeviceV1.Identify Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Identify Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILogOnDeviceV1.Identify(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfo)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ilogondevicev1.identify(v=AX.60)
ms:contentKeyID: 49847420
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILogOnDeviceV1.Identify
dev_langs:
- CSharp
- C++
- VB
---

# Identify Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Identifies the specified capture data.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Identify ( _
    captureData As IExtendedLogOnInfo _
) As String
'Usage
Dim instance As ILogOnDeviceV1
Dim captureData As IExtendedLogOnInfo
Dim returnValue As String

returnValue = instance.Identify(captureData)
```

``` csharp
string Identify(
    IExtendedLogOnInfo captureData
)
```

``` c++
String^ Identify(
    IExtendedLogOnInfo^ captureData
)
```

#### Parameters

  - captureData  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfo](iextendedlogoninfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The matched staff id if found, null otherwise  

## See Also

#### Reference

[ILogOnDeviceV1 Interface](ilogondevicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

