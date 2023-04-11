---
title: IItemV1.BatchNumberGroupId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BatchNumberGroupId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.BatchNumberGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.batchnumbergroupid(v=AX.60)
ms:contentKeyID: 49856570
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.BatchNumberGroupId
dev_langs:
- CSharp
- C++
- VB
---

# BatchNumberGroupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the batch number group id.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property BatchNumberGroupId As String
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As String

value = instance.BatchNumberGroupId

instance.BatchNumberGroupId = value
```

``` csharp
string BatchNumberGroupId { get; set; }
```

``` c++
property String^ BatchNumberGroupId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The batch number group id.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

