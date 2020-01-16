---
title: Barcode.DataEntry Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DataEntry Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.DataEntry
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.dataentry(v=AX.60)
ms:contentKeyID: 62214041
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.DataEntry
dev_langs:
- CSharp
- C++
- VB
---

# DataEntry Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DataEntry As String
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As String

value = instance.DataEntry

instance.DataEntry = value
```

``` csharp
[DataMemberAttribute]
public string DataEntry { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DataEntry {
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

