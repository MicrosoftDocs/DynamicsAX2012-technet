---
title: IPosTransactionV1.StoreAddress Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: StoreAddress Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.StoreAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv1.storeaddress(v=AX.60)
ms:contentKeyID: 47129204
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.StoreAddress
dev_langs:
- CSharp
- C++
- VB
---

# StoreAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the store address.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property StoreAddress As String
    Get
'Usage
Dim instance As IPosTransactionV1
Dim value As String

value = instance.StoreAddress
```

``` csharp
string StoreAddress { get; }
```

``` c++
property String^ StoreAddress {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosTransactionV1 Interface](ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

