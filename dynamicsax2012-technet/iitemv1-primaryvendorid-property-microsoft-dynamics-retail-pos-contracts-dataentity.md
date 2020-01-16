---
title: IItemV1.PrimaryVendorId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PrimaryVendorId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.PrimaryVendorId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.primaryvendorid(v=AX.60)
ms:contentKeyID: 49833072
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.PrimaryVendorId
dev_langs:
- CSharp
- C++
- VB
---

# PrimaryVendorId Property

Gets or sets the primary vendor id.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PrimaryVendorId As String
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As String

value = instance.PrimaryVendorId

instance.PrimaryVendorId = value
```

``` csharp
string PrimaryVendorId { get; set; }
```

``` c++
property String^ PrimaryVendorId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The primary vendor id.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

