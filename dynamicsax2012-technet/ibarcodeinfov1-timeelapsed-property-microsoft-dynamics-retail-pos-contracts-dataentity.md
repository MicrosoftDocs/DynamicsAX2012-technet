---
title: IBarcodeInfoV1.TimeElapsed Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TimeElapsed Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.TimeElapsed
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.timeelapsed(v=AX.60)
ms:contentKeyID: 47129133
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.TimeElapsed
dev_langs:
- CSharp
- C++
- VB
---

# TimeElapsed Property

Gets or sets the time difference between start and finish.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TimeElapsed As TimeSpan
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As TimeSpan

value = instance.TimeElapsed

instance.TimeElapsed = value
```

``` csharp
TimeSpan TimeElapsed { get; set; }
```

``` c++
property TimeSpan TimeElapsed {
    TimeSpan get ();
    void set (TimeSpan value);
}
```

#### Property Value

Type: [System.TimeSpan](https://technet.microsoft.com/en-us/library/269ew577\(v=ax.60\))  
The [System.TimeSpan](https://technet.microsoft.com/en-us/library/269ew577\(v=ax.60\)) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

