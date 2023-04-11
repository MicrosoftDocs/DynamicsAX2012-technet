---
title: ProductProperty.ValueString Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValueString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.ValueString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.valuestring(v=AX.60)
ms:contentKeyID: 62213816
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.ValueString
dev_langs:
- CSharp
- C++
- VB
---

# ValueString Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the value of the Value object. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ValueString As String
    Get
    Friend Set
'Usage
Dim instance As ProductProperty
Dim value As String

value = instance.ValueString
```

``` csharp
[DataMemberAttribute]
public string ValueString { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ValueString {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

