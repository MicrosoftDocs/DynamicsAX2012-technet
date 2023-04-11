---
title: IBarcodeInfoV1.BarcodeType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BarcodeType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.BarcodeType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.barcodetype(v=AX.60)
ms:contentKeyID: 47128189
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.BarcodeType
dev_langs:
- CSharp
- C++
- VB
---

# BarcodeType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the barcode type, which is an enumerated constant defined in OPOSScanDataType that indicates the barcode type.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property BarcodeType As OPOSScanDataType
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As OPOSScanDataType

value = instance.BarcodeType

instance.BarcodeType = value
```

``` csharp
OPOSScanDataType BarcodeType { get; set; }
```

``` c++
property OPOSScanDataType BarcodeType {
    OPOSScanDataType get ();
    void set (OPOSScanDataType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType](oposscandatatype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType](oposscandatatype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

