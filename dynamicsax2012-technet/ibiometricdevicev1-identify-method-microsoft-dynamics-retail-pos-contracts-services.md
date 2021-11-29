---
title: IBiometricDeviceV1.Identify Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Identify Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBiometricDeviceV1.Identify(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfo,System.Collections.Generic.ICollection{System.Byte[]})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ibiometricdevicev1.identify(v=AX.60)
ms:contentKeyID: 49843783
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBiometricDeviceV1.Identify
dev_langs:
- CSharp
- C++
- VB
---

# Identify Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Identifies the specified capture data from the available candidate biometric templates.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Identify ( _
    captureData As IExtendedLogOnInfo, _
    candidates As ICollection(Of Byte()) _
) As String
'Usage
Dim instance As IBiometricDeviceV1
Dim captureData As IExtendedLogOnInfo
Dim candidates As ICollection(Of Byte())
Dim returnValue As String

returnValue = instance.Identify(captureData, _
    candidates)
```

``` csharp
string Identify(
    IExtendedLogOnInfo captureData,
    ICollection<byte[]> candidates
)
```

``` c++
String^ Identify(
    IExtendedLogOnInfo^ captureData, 
    ICollection<array<unsigned char>^>^ candidates
)
```

#### Parameters

  - captureData  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfo](iextendedlogoninfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - candidates  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]\>  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Log on key mapped to the staff.  

## See Also

#### Reference

[IBiometricDeviceV1 Interface](ibiometricdevicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

