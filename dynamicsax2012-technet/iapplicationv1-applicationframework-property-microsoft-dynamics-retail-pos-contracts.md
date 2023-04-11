---
title: IApplicationV1.ApplicationFramework Property  (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: ApplicationFramework Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.ApplicationFramework
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.iapplicationv1.applicationframework(v=AX.60)
ms:contentKeyID: 47128695
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.ApplicationFramework
dev_langs:
- CSharp
- C++
- VB
---

# ApplicationFramework Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the application framework.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property ApplicationFramework As IApplicationFramework
    Get
'Usage
Dim instance As IApplicationV1
Dim value As IApplicationFramework

value = instance.ApplicationFramework
```

``` csharp
IApplicationFramework ApplicationFramework { get; }
```

``` c++
property IApplicationFramework^ ApplicationFramework {
    IApplicationFramework^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.UI.IApplicationFramework](iapplicationframework-interface-microsoft-dynamics-retail-pos-contracts-ui.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.UI.IApplicationFramework](iapplicationframework-interface-microsoft-dynamics-retail-pos-contracts-ui.md) value.  

## See Also

#### Reference

[IApplicationV1 Interface](iapplicationv1-interface-microsoft-dynamics-retail-pos-contracts.md)

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)

