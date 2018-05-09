---
title: CartLineData.LinkedParentLineId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LinkedParentLineId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.LinkedParentLineId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.linkedparentlineid(v=AX.60)
ms:contentKeyID: 62214413
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.LinkedParentLineId
dev_langs:
- CSharp
- C++
- VB
---

# LinkedParentLineId Property

Gets the line id of the product to which this product is linked to.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LinkedParentLineId As String
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As String

value = instance.LinkedParentLineId

instance.LinkedParentLineId = value
```

``` csharp
[DataMemberAttribute]
public string LinkedParentLineId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LinkedParentLineId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

