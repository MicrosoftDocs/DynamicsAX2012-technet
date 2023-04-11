---
title: ProductRefiner.SourceValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SourceValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.SourceValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefiner.sourcevalue(v=AX.60)
ms:contentKeyID: 65321178
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.SourceValue
dev_langs:
- CSharp
- C++
- VB
---

# SourceValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the ProductRefinerSource enumeration. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SourceValue As Integer
    Get
    Set
'Usage
Dim instance As ProductRefiner
Dim value As Integer

value = instance.SourceValue

instance.SourceValue = value
```

``` csharp
[DataMemberAttribute]
public int SourceValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int SourceValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ProductRefiner Class](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

