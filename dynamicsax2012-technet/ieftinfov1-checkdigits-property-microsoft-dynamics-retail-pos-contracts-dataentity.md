---
title: IEFTInfoV1.CheckDigits Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CheckDigits Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.CheckDigits
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.checkdigits(v=AX.60)
ms:contentKeyID: 47128039
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.CheckDigits
dev_langs:
- CSharp
- C++
- VB
---

# CheckDigits Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the check digits.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CheckDigits As String
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As String

value = instance.CheckDigits

instance.CheckDigits = value
```

``` csharp
string CheckDigits { get; set; }
```

``` c++
property String^ CheckDigits {
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

