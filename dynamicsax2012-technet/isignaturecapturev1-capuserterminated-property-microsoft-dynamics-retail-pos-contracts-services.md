---
title: ISignatureCaptureV1.CapUserTerminated Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CapUserTerminated Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCaptureV1.CapUserTerminated
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.isignaturecapturev1.capuserterminated(v=AX.60)
ms:contentKeyID: 49849097
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCaptureV1.CapUserTerminated
dev_langs:
- CSharp
- C++
- VB
---

# CapUserTerminated Property

Gets a flag to identify that user is able to terminate capture by checking a completion box, pressing a completion button, or perfoming some other interaction with the device.This property is initialized by the Load method.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property CapUserTerminated As Boolean
    Get
'Usage
Dim instance As ISignatureCaptureV1
Dim value As Boolean

value = instance.CapUserTerminated
```

``` csharp
bool CapUserTerminated { get; }
```

``` c++
property bool CapUserTerminated {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ISignatureCaptureV1 Interface](isignaturecapturev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

