---
title: IScanInfoV1.EntryType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: EntryType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfoV1.EntryType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iscaninfov1.entrytype(v=AX.60)
ms:contentKeyID: 47128819
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfoV1.EntryType
dev_langs:
- CSharp
- C++
- VB
---

# EntryType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the way the barcode was entered.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property EntryType As BarcodeEntryType
    Get
    Set
'Usage
Dim instance As IScanInfoV1
Dim value As BarcodeEntryType

value = instance.EntryType

instance.EntryType = value
```

``` csharp
BarcodeEntryType EntryType { get; set; }
```

``` c++
property BarcodeEntryType EntryType {
    BarcodeEntryType get ();
    void set (BarcodeEntryType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeEntryType](barcodeentrytype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeEntryType](barcodeentrytype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md) value.  

## See Also

#### Reference

[IScanInfoV1 Interface](iscaninfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

