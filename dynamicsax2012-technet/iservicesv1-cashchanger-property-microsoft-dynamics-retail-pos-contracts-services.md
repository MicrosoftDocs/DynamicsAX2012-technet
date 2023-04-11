---
title: IServicesV1.CashChanger Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CashChanger Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.CashChanger
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iservicesv1.cashchanger(v=AX.60)
ms:contentKeyID: 47343974
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.CashChanger
dev_langs:
- CSharp
- C++
- VB
---

# CashChanger Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Cash changer service

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property CashChanger As ICashChanger
    Get
'Usage
Dim instance As IServicesV1
Dim value As ICashChanger

value = instance.CashChanger
```

``` csharp
ICashChanger CashChanger { get; }
```

``` c++
property ICashChanger^ CashChanger {
    ICashChanger^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChanger](icashchanger-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [ICashChanger](icashchanger-interface-microsoft-dynamics-retail-pos-contracts-services.md) .  

## See Also

#### Reference

[IServicesV1 Interface](iservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

