---
title: Barcode.ColorName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ColorName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.ColorName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.colorname(v=AX.60)
ms:contentKeyID: 62210930
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.ColorName
dev_langs:
- CSharp
- C++
- VB
---

# ColorName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ColorName As String
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As String

value = instance.ColorName

instance.ColorName = value
```

``` csharp
[DataMemberAttribute]
public string ColorName { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ColorName {
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

