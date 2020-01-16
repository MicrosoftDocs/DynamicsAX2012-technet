---
title: Cart.AttributeValues Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AttributeValues Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.AttributeValues
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.attributevalues(v=AX.60)
ms:contentKeyID: 49824304
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.AttributeValues
dev_langs:
- CSharp
- C++
- VB
---

# AttributeValues Property

Gets or sets the sales attributes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AttributeValues As IList(Of AttributeValueBase)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As IList(Of AttributeValueBase)

value = instance.AttributeValues

instance.AttributeValues = value
```

``` csharp
[DataMemberAttribute]
public IList<AttributeValueBase> AttributeValues { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<AttributeValueBase^>^ AttributeValues {
    IList<AttributeValueBase^>^ get ();
    void set (IList<AttributeValueBase^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[AttributeValueBase](attributevaluebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

