---
title: IApplicationServiceV1.ApplicationWindowIcon Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ApplicationWindowIcon Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.ApplicationWindowIcon
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iapplicationservicev1.applicationwindowicon(v=AX.60)
ms:contentKeyID: 47344367
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.ApplicationWindowIcon
dev_langs:
- CSharp
- C++
- VB
---

# ApplicationWindowIcon Property

Returns the icon displayed for the application in the Windows task bar.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property ApplicationWindowIcon As Icon
    Get
'Usage
Dim instance As IApplicationServiceV1
Dim value As Icon

value = instance.ApplicationWindowIcon
```

``` csharp
Icon ApplicationWindowIcon { get; }
```

``` c++
property Icon^ ApplicationWindowIcon {
    Icon^ get ();
}
```

#### Property Value

Type: [System.Drawing.Icon](https://technet.microsoft.com/library/wkat843k\(v=ax.60\))  
The [Icon](https://technet.microsoft.com/library/wkat843k\(v=ax.60\)) icon.  

## See Also

#### Reference

[IApplicationServiceV1 Interface](iapplicationservicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

