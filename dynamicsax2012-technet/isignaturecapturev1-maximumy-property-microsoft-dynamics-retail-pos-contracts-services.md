---
title: ISignatureCaptureV1.MaximumY Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: MaximumY Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCaptureV1.MaximumY
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.isignaturecapturev1.maximumy(v=AX.60)
ms:contentKeyID: 49821813
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCaptureV1.MaximumY
dev_langs:
- CSharp
- C++
- VB
---

# MaximumY Property

Gets the maximum vertical coordinate of the signature capture device.This property is initialized by the Load method.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property MaximumY As Integer
    Get
'Usage
Dim instance As ISignatureCaptureV1
Dim value As Integer

value = instance.MaximumY
```

``` csharp
int MaximumY { get; }
```

``` c++
property int MaximumY {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ISignatureCaptureV1 Interface](isignaturecapturev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

