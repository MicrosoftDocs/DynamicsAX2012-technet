---
title: ISignatureCaptureV1.CapDisplay Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CapDisplay Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCaptureV1.CapDisplay
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isignaturecapturev1.capdisplay(v=AX.60)
ms:contentKeyID: 49856239
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCaptureV1.CapDisplay
dev_langs:
- CSharp
- C++
- VB
---

# CapDisplay Property

Gets a flag to identify that device is able to display form or data entry screen.This property is initialized by the Load method.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property CapDisplay As Boolean
    Get
'Usage
Dim instance As ISignatureCaptureV1
Dim value As Boolean

value = instance.CapDisplay
```

``` csharp
bool CapDisplay { get; }
```

``` c++
property bool CapDisplay {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ISignatureCaptureV1 Interface](isignaturecapturev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

