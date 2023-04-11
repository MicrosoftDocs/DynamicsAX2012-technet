---
title: Barcode.BarcodeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BarcodeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.BarcodeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.barcodeid(v=AX.60)
ms:contentKeyID: 62208493
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.BarcodeId
dev_langs:
- CSharp
- C++
- VB
---

# BarcodeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property BarcodeId As String
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As String

value = instance.BarcodeId

instance.BarcodeId = value
```

``` csharp
[DataMemberAttribute]
public string BarcodeId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ BarcodeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

