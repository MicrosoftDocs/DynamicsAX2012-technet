---
title: ItemUnit.VariantInventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VariantInventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit.VariantInventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itemunit.variantinventorydimensionid(v=AX.60)
ms:contentKeyID: 49823502
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit.VariantInventoryDimensionId
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
<DataMemberAttribute> _
<ColumnAttribute("VARIANTINVENTDIMID")> _
Public Property VariantInventoryDimensionId As String
    Get
    Set
'Usage
Dim instance As ItemUnit
Dim value As String

value = instance.VariantInventoryDimensionId

instance.VariantInventoryDimensionId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("VARIANTINVENTDIMID")]
public string VariantInventoryDimensionId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"VARIANTINVENTDIMID")]
public:
property String^ VariantInventoryDimensionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The variant inventory dimension identifier.  

## See Also

#### Reference

[ItemUnit Class](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

