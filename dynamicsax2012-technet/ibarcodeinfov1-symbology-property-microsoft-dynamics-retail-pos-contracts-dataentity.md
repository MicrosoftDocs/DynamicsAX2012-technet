---
title: IBarcodeInfoV1.Symbology Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Symbology Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.Symbology
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.symbology(v=AX.60)
ms:contentKeyID: 47128564
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.Symbology
dev_langs:
- CSharp
- C++
- VB
---

# Symbology Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets symbology, which is an enumerated constant that indicates the type of barcode.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Symbology As BarcodeType
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As BarcodeType

value = instance.Symbology

instance.Symbology = value
```

``` csharp
BarcodeType Symbology { get; set; }
```

``` c++
property BarcodeType Symbology {
    BarcodeType get ();
    void set (BarcodeType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeType](barcodetype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeType](barcodetype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

