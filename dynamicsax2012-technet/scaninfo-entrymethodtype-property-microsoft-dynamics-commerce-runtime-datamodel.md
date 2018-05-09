---
title: ScanInfo.EntryMethodType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EntryMethodType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ScanInfo.EntryMethodType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.scaninfo.entrymethodtype(v=AX.60)
ms:contentKeyID: 62204139
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ScanInfo.EntryMethodType
dev_langs:
- CSharp
- C++
- VB
---

# EntryMethodType Property

Gets or sets the way the barcode was entered.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property EntryMethodType As BarcodeEntryMethodType
    Get
    Set
'Usage
Dim instance As ScanInfo
Dim value As BarcodeEntryMethodType

value = instance.EntryMethodType

instance.EntryMethodType = value
```

``` csharp
public BarcodeEntryMethodType EntryMethodType { get; set; }
```

``` c++
public:
property BarcodeEntryMethodType EntryMethodType {
    BarcodeEntryMethodType get ();
    void set (BarcodeEntryMethodType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeEntryMethodType](barcodeentrymethodtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [BarcodeEntryMethodType](barcodeentrymethodtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ScanInfo Class](scaninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

