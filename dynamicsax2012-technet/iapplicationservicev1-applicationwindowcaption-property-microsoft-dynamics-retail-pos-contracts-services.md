---
title: IApplicationServiceV1.ApplicationWindowCaption Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ApplicationWindowCaption Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.ApplicationWindowCaption
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iapplicationservicev1.applicationwindowcaption(v=AX.60)
ms:contentKeyID: 47344432
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.ApplicationWindowCaption
dev_langs:
- CSharp
- C++
- VB
---

# ApplicationWindowCaption Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the text displayed for the application in the Windows task bar.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property ApplicationWindowCaption As String
    Get
'Usage
Dim instance As IApplicationServiceV1
Dim value As String

value = instance.ApplicationWindowCaption
```

``` csharp
string ApplicationWindowCaption { get; }
```

``` c++
property String^ ApplicationWindowCaption {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) string.  

## See Also

#### Reference

[IApplicationServiceV1 Interface](iapplicationservicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

