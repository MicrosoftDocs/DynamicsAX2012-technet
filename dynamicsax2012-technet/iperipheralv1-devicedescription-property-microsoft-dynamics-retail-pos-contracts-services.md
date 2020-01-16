---
title: IPeripheralV1.DeviceDescription Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: DeviceDescription Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralV1.DeviceDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralv1.devicedescription(v=AX.60)
ms:contentKeyID: 49849810
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralV1.DeviceDescription
dev_langs:
- CSharp
- C++
- VB
---

# DeviceDescription Property

Device Description (may be null or empty)

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property DeviceDescription As String
    Get
'Usage
Dim instance As IPeripheralV1
Dim value As String

value = instance.DeviceDescription
```

``` csharp
string DeviceDescription { get; }
```

``` c++
property String^ DeviceDescription {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IPeripheralV1 Interface](iperipheralv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

