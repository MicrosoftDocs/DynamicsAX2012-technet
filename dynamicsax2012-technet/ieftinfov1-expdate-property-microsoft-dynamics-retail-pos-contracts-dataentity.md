---
title: IEFTInfoV1.ExpDate Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ExpDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.ExpDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.expdate(v=AX.60)
ms:contentKeyID: 47128836
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.ExpDate
dev_langs:
- CSharp
- C++
- VB
---

# ExpDate Property

The expiration date if the information was entered manually.

After the transaction has been processed, this property holds the expiration date.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ExpDate As String
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As String

value = instance.ExpDate

instance.ExpDate = value
```

``` csharp
string ExpDate { get; set; }
```

``` c++
property String^ ExpDate {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

