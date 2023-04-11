---
title: IInfoCodeLineItemV1.LinkedInfoCodeId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LinkedInfoCodeId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.LinkedInfoCodeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemv1.linkedinfocodeid(v=AX.60)
ms:contentKeyID: 49844492
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.LinkedInfoCodeId
dev_langs:
- CSharp
- C++
- VB
---

# LinkedInfoCodeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The id of the linked infocode.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LinkedInfoCodeId As String
    Get
    Set
'Usage
Dim instance As IInfoCodeLineItemV1
Dim value As String

value = instance.LinkedInfoCodeId

instance.LinkedInfoCodeId = value
```

``` csharp
string LinkedInfoCodeId { get; set; }
```

``` c++
property String^ LinkedInfoCodeId {
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

