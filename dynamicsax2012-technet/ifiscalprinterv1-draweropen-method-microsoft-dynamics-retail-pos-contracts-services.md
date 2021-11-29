---
title: IFiscalPrinterV1.DrawerOpen Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: DrawerOpen Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.DrawerOpen
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.draweropen(v=AX.60)
ms:contentKeyID: 62203677
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.DrawerOpen
dev_langs:
- CSharp
- C++
- VB
---

# DrawerOpen Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Check if cash drawer is open.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function DrawerOpen As Boolean
'Usage
Dim instance As IFiscalPrinterV1
Dim returnValue As Boolean

returnValue = instance.DrawerOpen()
```

``` csharp
bool DrawerOpen()
```

``` c++
bool DrawerOpen()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if open, false otherwise.  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

