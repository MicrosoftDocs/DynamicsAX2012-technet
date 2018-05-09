---
title: ProductProperty.AttributeValueId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AttributeValueId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.AttributeValueId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.attributevalueid(v=AX.60)
ms:contentKeyID: 62215136
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.AttributeValueId
dev_langs:
- CSharp
- C++
- VB
---

# AttributeValueId Property

Gets or sets the underlying attribute id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALUE")> _
<DataMemberAttribute> _
Public Property AttributeValueId As Long
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As Long

value = instance.AttributeValueId

instance.AttributeValueId = value
```

``` csharp
[ColumnAttribute("VALUE")]
[DataMemberAttribute]
public long AttributeValueId { get; set; }
```

``` c++
[ColumnAttribute(L"VALUE")]
[DataMemberAttribute]
public:
property long long AttributeValueId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The attribute id.  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

