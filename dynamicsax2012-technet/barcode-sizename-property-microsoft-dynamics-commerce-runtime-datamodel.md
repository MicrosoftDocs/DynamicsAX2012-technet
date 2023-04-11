---
title: Barcode.SizeName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SizeName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.SizeName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.sizename(v=AX.60)
ms:contentKeyID: 62214227
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.SizeName
dev_langs:
- CSharp
- C++
- VB
---

# SizeName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SizeName As String
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As String

value = instance.SizeName

instance.SizeName = value
```

``` csharp
[DataMemberAttribute]
public string SizeName { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ SizeName {
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

