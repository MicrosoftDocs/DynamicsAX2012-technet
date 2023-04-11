---
title: IBarcodeInfoV1.SalespersonId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SalespersonId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.SalespersonId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.salespersonid(v=AX.60)
ms:contentKeyID: 47128111
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.SalespersonId
dev_langs:
- CSharp
- C++
- VB
---

# SalespersonId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales person ID found in the barcode - Internaltype = 6.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SalespersonId As String
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As String

value = instance.SalespersonId

instance.SalespersonId = value
```

``` csharp
string SalespersonId { get; set; }
```

``` c++
property String^ SalespersonId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

