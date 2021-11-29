---
title: IApplicationServiceV1.LoginWindowImage Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: LoginWindowImage Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.LoginWindowImage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iapplicationservicev1.loginwindowimage(v=AX.60)
ms:contentKeyID: 47344188
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.LoginWindowImage
dev_langs:
- CSharp
- C++
- VB
---

# LoginWindowImage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the image displayed on the logon dialog in the upper-left corner.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property LoginWindowImage As Image
    Get
'Usage
Dim instance As IApplicationServiceV1
Dim value As Image

value = instance.LoginWindowImage
```

``` csharp
Image LoginWindowImage { get; }
```

``` c++
property Image^ LoginWindowImage {
    Image^ get ();
}
```

#### Property Value

Type: [System.Drawing.Image](https://technet.microsoft.com/library/k7e7b2kd\(v=ax.60\))  
The [Image](https://technet.microsoft.com/library/k7e7b2kd\(v=ax.60\)) image.  

## See Also

#### Reference

[IApplicationServiceV1 Interface](iapplicationservicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

