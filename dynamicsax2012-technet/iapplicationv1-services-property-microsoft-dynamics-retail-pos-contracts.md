---
title: IApplicationV1.Services Property  (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: Services Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.Services
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.iapplicationv1.services(v=AX.60)
ms:contentKeyID: 47129212
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.Services
dev_langs:
- CSharp
- C++
- VB
---

# Services Property

Get the application services.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Services As IServices
    Get
'Usage
Dim instance As IApplicationV1
Dim value As IServices

value = instance.Services
```

``` csharp
IServices Services { get; }
```

``` c++
property IServices^ Services {
    IServices^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServices](iservices-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServices](iservices-interface-microsoft-dynamics-retail-pos-contracts-services.md) value.  

## See Also

#### Reference

[IApplicationV1 Interface](iapplicationv1-interface-microsoft-dynamics-retail-pos-contracts.md)

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)

