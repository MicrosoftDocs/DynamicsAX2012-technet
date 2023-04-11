---
title: IServicesV3.EFTServiceOperations Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: EFTServiceOperations Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV3.EFTServiceOperations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iservicesv3.eftserviceoperations(v=AX.60)
ms:contentKeyID: 62203314
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV3.EFTServiceOperations
dev_langs:
- CSharp
- C++
- VB
---

# EFTServiceOperations Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Bank operations service

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property EFTServiceOperations As IEFTServiceOperationsService
    Get
'Usage
Dim instance As IServicesV3
Dim value As IEFTServiceOperationsService

value = instance.EFTServiceOperations
```

``` csharp
IEFTServiceOperationsService EFTServiceOperations { get; }
```

``` c++
property IEFTServiceOperationsService^ EFTServiceOperations {
    IEFTServiceOperationsService^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTServiceOperationsService](ieftserviceoperationsservice-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [IEFTServiceOperationsService](ieftserviceoperationsservice-interface-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[IServicesV3 Interface](iservicesv3-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

