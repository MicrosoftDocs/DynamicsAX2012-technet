---
title: IItemV1.PbaInventItemGroupId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PbaInventItemGroupId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.PbaInventItemGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.pbainventitemgroupid(v=AX.60)
ms:contentKeyID: 49851439
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.PbaInventItemGroupId
dev_langs:
- CSharp
- C++
- VB
---

# PbaInventItemGroupId Property

Gets or sets the pba invent item group id.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PbaInventItemGroupId As String
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As String

value = instance.PbaInventItemGroupId

instance.PbaInventItemGroupId = value
```

``` csharp
string PbaInventItemGroupId { get; set; }
```

``` c++
property String^ PbaInventItemGroupId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The pba invent item group id.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

