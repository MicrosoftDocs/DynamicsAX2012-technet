---
title: IApplicationV1.Triggers Property  (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: Triggers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.Triggers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.iapplicationv1.triggers(v=AX.60)
ms:contentKeyID: 47129344
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.Triggers
dev_langs:
- CSharp
- C++
- VB
---

# Triggers Property

Get the application triggers.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Triggers As ITriggers
    Get
'Usage
Dim instance As IApplicationV1
Dim value As ITriggers

value = instance.Triggers
```

``` csharp
ITriggers Triggers { get; }
```

``` c++
property ITriggers^ Triggers {
    ITriggers^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggers](itriggers-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggers](itriggers-interface-microsoft-dynamics-retail-pos-contracts-triggers.md) value.  

## See Also

#### Reference

[IApplicationV1 Interface](iapplicationv1-interface-microsoft-dynamics-retail-pos-contracts.md)

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)

