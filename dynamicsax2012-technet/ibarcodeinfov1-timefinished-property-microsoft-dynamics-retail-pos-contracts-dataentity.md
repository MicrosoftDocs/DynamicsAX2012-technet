---
title: IBarcodeInfoV1.TimeFinished Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TimeFinished Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.TimeFinished
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.timefinished(v=AX.60)
ms:contentKeyID: 47128449
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.TimeFinished
dev_langs:
- CSharp
- C++
- VB
---

# TimeFinished Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the timestamp when the processing of the transaction is finished.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TimeFinished As DateTime
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As DateTime

value = instance.TimeFinished

instance.TimeFinished = value
```

``` csharp
DateTime TimeFinished { get; set; }
```

``` c++
property DateTime TimeFinished {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
The [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

