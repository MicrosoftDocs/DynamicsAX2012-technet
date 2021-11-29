---
title: IPrinterV2.SetUpPrinter Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SetUpPrinter Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinterV2.SetUpPrinter(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprinterv2.setupprinter(v=AX.60)
ms:contentKeyID: 49834852
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinterV2.SetUpPrinter
dev_langs:
- CSharp
- C++
- VB
---

# SetUpPrinter Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Setup printer object with device settings

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SetUpPrinter ( _
    deviceTypeName As String, _
    deviceName As String, _
    deviceDescription As String _
)
'Usage
Dim instance As IPrinterV2
Dim deviceTypeName As String
Dim deviceName As String
Dim deviceDescription As String

instance.SetUpPrinter(deviceTypeName, _
    deviceName, deviceDescription)
```

``` csharp
void SetUpPrinter(
    string deviceTypeName,
    string deviceName,
    string deviceDescription
)
```

``` c++
void SetUpPrinter(
    String^ deviceTypeName, 
    String^ deviceName, 
    String^ deviceDescription
)
```

#### Parameters

  - deviceTypeName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - deviceName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - deviceDescription  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IPrinterV2 Interface](iprinterv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

