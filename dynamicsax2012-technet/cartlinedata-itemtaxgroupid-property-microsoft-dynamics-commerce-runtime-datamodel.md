---
title: CartLineData.ItemTaxGroupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemTaxGroupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ItemTaxGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.itemtaxgroupid(v=AX.60)
ms:contentKeyID: 65322896
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ItemTaxGroupId
dev_langs:
- CSharp
- C++
- VB
---

# ItemTaxGroupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ITEMTAXGROUPID")> _
<DataMemberAttribute> _
Public Property ItemTaxGroupId As String
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As String

value = instance.ItemTaxGroupId

instance.ItemTaxGroupId = value
```

``` csharp
[ColumnAttribute("ITEMTAXGROUPID")]
[DataMemberAttribute]
public string ItemTaxGroupId { get; set; }
```

``` c++
[ColumnAttribute(L"ITEMTAXGROUPID")]
[DataMemberAttribute]
public:
property String^ ItemTaxGroupId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

