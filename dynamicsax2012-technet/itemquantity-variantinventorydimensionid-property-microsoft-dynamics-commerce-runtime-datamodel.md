---
title: ItemQuantity.VariantInventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VariantInventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemQuantity.VariantInventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemquantity.variantinventorydimensionid(v=AX.60)
ms:contentKeyID: 49847839
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemQuantity.VariantInventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# VariantInventoryDimensionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the variant inventory dimension identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property VariantInventoryDimensionId As String
    Get
    Set
'Usage
Dim instance As ItemQuantity
Dim value As String

value = instance.VariantInventoryDimensionId

instance.VariantInventoryDimensionId = value
```

``` csharp
[DataMemberAttribute]
public string VariantInventoryDimensionId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ VariantInventoryDimensionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The variant inventory dimension identifier.  

## See Also

#### Reference

[ItemQuantity Class](itemquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

