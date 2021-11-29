---
title: Barcode.InventoryStyleId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventoryStyleId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.InventoryStyleId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.inventorystyleid(v=AX.60)
ms:contentKeyID: 62210772
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.InventoryStyleId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryStyleId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventoryStyleId As String
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As String

value = instance.InventoryStyleId

instance.InventoryStyleId = value
```

``` csharp
[DataMemberAttribute]
public string InventoryStyleId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventoryStyleId {
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

