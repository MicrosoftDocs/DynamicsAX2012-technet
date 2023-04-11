---
title: IRetailTransactionV2.InventSiteId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InventSiteId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV2.InventSiteId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv2.inventsiteid(v=AX.60)
ms:contentKeyID: 49843556
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV2.InventSiteId
dev_langs:
- CSharp
- C++
- VB
---

# InventSiteId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Site ID

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property InventSiteId As String
    Get
    Set
'Usage
Dim instance As IRetailTransactionV2
Dim value As String

value = instance.InventSiteId

instance.InventSiteId = value
```

``` csharp
string InventSiteId { get; set; }
```

``` c++
property String^ InventSiteId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV2 Interface](iretailtransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

