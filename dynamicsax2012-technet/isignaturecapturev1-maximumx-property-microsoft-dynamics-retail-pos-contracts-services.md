---
title: ISignatureCaptureV1.MaximumX Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: MaximumX Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCaptureV1.MaximumX
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isignaturecapturev1.maximumx(v=AX.60)
ms:contentKeyID: 49820755
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCaptureV1.MaximumX
dev_langs:
- CSharp
- C++
- VB
---

# MaximumX Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the maximum horizontal coordinate of the signature capture device.This property is initialized by the Load method.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property MaximumX As Integer
    Get
'Usage
Dim instance As ISignatureCaptureV1
Dim value As Integer

value = instance.MaximumX
```

``` csharp
int MaximumX { get; }
```

``` c++
property int MaximumX {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ISignatureCaptureV1 Interface](isignaturecapturev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

