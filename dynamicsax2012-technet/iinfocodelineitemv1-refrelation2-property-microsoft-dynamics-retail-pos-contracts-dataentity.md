---
title: IInfoCodeLineItemV1.RefRelation2 Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RefRelation2 Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.RefRelation2
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemv1.refrelation2(v=AX.60)
ms:contentKeyID: 49831767
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.RefRelation2
dev_langs:
- CSharp
- C++
- VB
---

# RefRelation2 Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Second field in the primary key of what activated the infocode.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property RefRelation2 As String
    Get
    Set
'Usage
Dim instance As IInfoCodeLineItemV1
Dim value As String

value = instance.RefRelation2

instance.RefRelation2 = value
```

``` csharp
string RefRelation2 { get; set; }
```

``` c++
property String^ RefRelation2 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IInfoCodeLineItemV1 Interface](iinfocodelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

