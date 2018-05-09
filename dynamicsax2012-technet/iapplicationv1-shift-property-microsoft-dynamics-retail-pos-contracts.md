---
title: IApplicationV1.Shift Property  (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: Shift Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.Shift
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.iapplicationv1.shift(v=AX.60)
ms:contentKeyID: 47128844
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.Shift
dev_langs:
- CSharp
- C++
- VB
---

# Shift Property

Gets the current shift.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Shift As IPosBatchStaging
    Get
'Usage
Dim instance As IApplicationV1
Dim value As IPosBatchStaging

value = instance.Shift
```

``` csharp
IPosBatchStaging Shift { get; }
```

``` c++
property IPosBatchStaging^ Shift {
    IPosBatchStaging^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStaging](iposbatchstaging-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStaging](iposbatchstaging-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) value.  

## See Also

#### Reference

[IApplicationV1 Interface](iapplicationv1-interface-microsoft-dynamics-retail-pos-contracts.md)

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)

