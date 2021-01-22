---
title: Barcode.InventoryColorId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventoryColorId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.InventoryColorId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.inventorycolorid(v=AX.60)
ms:contentKeyID: 62207736
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.InventoryColorId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryColorId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventoryColorId As String
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As String

value = instance.InventoryColorId

instance.InventoryColorId = value
```

``` csharp
[DataMemberAttribute]
public string InventoryColorId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventoryColorId {
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

