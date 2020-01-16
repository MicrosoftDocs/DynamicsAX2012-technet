---
title: IServicesV2.Charges Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Charges Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV2.Charges
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iservicesv2.charges(v=AX.60)
ms:contentKeyID: 49850715
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV2.Charges
dev_langs:
- CSharp
- C++
- VB
---

# Charges Property

Gets the charges service.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Charges As ICharges
    Get
'Usage
Dim instance As IServicesV2
Dim value As ICharges

value = instance.Charges
```

``` csharp
ICharges Charges { get; }
```

``` c++
property ICharges^ Charges {
    ICharges^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICharges](icharges-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [ICharges](icharges-interface-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[IServicesV2 Interface](iservicesv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

