---
title: ItemBarcode.RetailVariantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetailVariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.RetailVariantId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itembarcode.retailvariantid(v=AX.60)
ms:contentKeyID: 62213359
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.RetailVariantId
dev_langs:
- CSharp
- C++
- VB
---

# RetailVariantId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the RetailVariant Identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RETAILVARIANTID")> _
<DataMemberAttribute> _
Public Property RetailVariantId As String
    Get
    Friend Set
'Usage
Dim instance As ItemBarcode
Dim value As String

value = instance.RetailVariantId
```

``` csharp
[ColumnAttribute("RETAILVARIANTID")]
[DataMemberAttribute]
public string RetailVariantId { get; internal set; }
```

``` c++
[ColumnAttribute(L"RETAILVARIANTID")]
[DataMemberAttribute]
public:
property String^ RetailVariantId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ItemBarcode Class](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

