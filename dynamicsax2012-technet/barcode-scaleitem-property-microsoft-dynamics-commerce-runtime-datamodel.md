---
title: Barcode.ScaleItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ScaleItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.ScaleItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.scaleitem(v=AX.60)
ms:contentKeyID: 62210052
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.ScaleItem
dev_langs:
- CSharp
- C++
- VB
---

# ScaleItem Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ScaleItem As Boolean
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As Boolean

value = instance.ScaleItem

instance.ScaleItem = value
```

``` csharp
[DataMemberAttribute]
public bool ScaleItem { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool ScaleItem {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

