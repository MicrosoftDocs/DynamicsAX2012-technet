---
title: IServicesV1.SalesOrder Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SalesOrder Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.SalesOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iservicesv1.salesorder(v=AX.60)
ms:contentKeyID: 47344060
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.SalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrder Property

Sales order service

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property SalesOrder As ISalesOrder
    Get
'Usage
Dim instance As IServicesV1
Dim value As ISalesOrder

value = instance.SalesOrder
```

``` csharp
ISalesOrder SalesOrder { get; }
```

``` c++
property ISalesOrder^ SalesOrder {
    ISalesOrder^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrder](isalesorder-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [ISalesOrder](isalesorder-interface-microsoft-dynamics-retail-pos-contracts-services.md) .  

## See Also

#### Reference

[IServicesV1 Interface](iservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

