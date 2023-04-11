---
title: IPeripheralsV1.CashDrawer Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CashDrawer Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.CashDrawer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv1.cashdrawer(v=AX.60)
ms:contentKeyID: 47344383
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.CashDrawer
dev_langs:
- CSharp
- C++
- VB
---

# CashDrawer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the CashDrawer peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property CashDrawer As ICashDrawer
    Get
'Usage
Dim instance As IPeripheralsV1
Dim value As ICashDrawer

value = instance.CashDrawer
```

``` csharp
ICashDrawer CashDrawer { get; }
```

``` c++
property ICashDrawer^ CashDrawer {
    ICashDrawer^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashDrawer](icashdrawer-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The [ICashDrawer](icashdrawer-interface-microsoft-dynamics-retail-pos-contracts-services.md) cash drawer.  

## See Also

#### Reference

[IPeripheralsV1 Interface](iperipheralsv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

