---
title: ItemAvailableQuantity.VariantInventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VariantInventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailableQuantity.VariantInventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailablequantity.variantinventorydimensionid(v=AX.60)
ms:contentKeyID: 49852654
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailableQuantity.VariantInventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# VariantInventoryDimensionId Property

Gets or sets the variant inventory dimension identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VARIANTINVENTDIMID")> _
<DataMemberAttribute> _
Public Property VariantInventoryDimensionId As String
    Get
    Friend Set
'Usage
Dim instance As ItemAvailableQuantity
Dim value As String

value = instance.VariantInventoryDimensionId
```

``` csharp
[ColumnAttribute("VARIANTINVENTDIMID")]
[DataMemberAttribute]
public string VariantInventoryDimensionId { get; internal set; }
```

``` c++
[ColumnAttribute(L"VARIANTINVENTDIMID")]
[DataMemberAttribute]
public:
property String^ VariantInventoryDimensionId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The variant inventory dimension identifier.  

## See Also

#### Reference

[ItemAvailableQuantity Class](itemavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

