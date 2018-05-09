---
title: IBarcodeInfoV1.TimeStarted Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TimeStarted Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.TimeStarted
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.timestarted(v=AX.60)
ms:contentKeyID: 47129323
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.TimeStarted
dev_langs:
- CSharp
- C++
- VB
---

# TimeStarted Property

Gets or sets the timestamp when the processing of the transaction is started.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TimeStarted As DateTime
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As DateTime

value = instance.TimeStarted

instance.TimeStarted = value
```

``` csharp
DateTime TimeStarted { get; set; }
```

``` c++
property DateTime TimeStarted {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))  
The [System.DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\)) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

