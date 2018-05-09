---
title: IBarcodeInfoV1.InternalType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InternalType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.InternalType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.internaltype(v=AX.60)
ms:contentKeyID: 47129358
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.InternalType
dev_langs:
- CSharp
- C++
- VB
---

# InternalType Property

Gets or sets the internal type of a barcode. This is an enumerated constant that indicates the type of barcode.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property InternalType As BarcodeInternalType
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As BarcodeInternalType

value = instance.InternalType

instance.InternalType = value
```

``` csharp
BarcodeInternalType InternalType { get; set; }
```

``` c++
property BarcodeInternalType InternalType {
    BarcodeInternalType get ();
    void set (BarcodeInternalType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeInternalType](barcodeinternaltype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeInternalType](barcodeinternaltype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md) value.  

## See Also

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

[BarcodeInternalType](barcodeinternaltype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)

