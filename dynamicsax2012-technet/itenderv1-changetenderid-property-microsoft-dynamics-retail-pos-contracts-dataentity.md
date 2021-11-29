---
title: ITenderV1.ChangeTenderID Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ChangeTenderID Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV1.ChangeTenderID
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderv1.changetenderid(v=AX.60)
ms:contentKeyID: 49846719
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV1.ChangeTenderID
dev_langs:
- CSharp
- C++
- VB
---

# ChangeTenderID Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The tender ID used to pay charge

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ChangeTenderID As String
    Get
    Set
'Usage
Dim instance As ITenderV1
Dim value As String

value = instance.ChangeTenderID

instance.ChangeTenderID = value
```

``` csharp
string ChangeTenderID { get; set; }
```

``` c++
property String^ ChangeTenderID {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ITenderV1 Interface](itenderv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

