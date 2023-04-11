---
title: Barcode.EntryMethodType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EntryMethodType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.EntryMethodType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.entrymethodtype(v=AX.60)
ms:contentKeyID: 62213469
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.EntryMethodType
dev_langs:
- CSharp
- C++
- VB
---

# EntryMethodType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property EntryMethodType As BarcodeEntryMethodType
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As BarcodeEntryMethodType

value = instance.EntryMethodType

instance.EntryMethodType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public BarcodeEntryMethodType EntryMethodType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property BarcodeEntryMethodType EntryMethodType {
    BarcodeEntryMethodType get ();
    void set (BarcodeEntryMethodType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeEntryMethodType](barcodeentrymethodtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

