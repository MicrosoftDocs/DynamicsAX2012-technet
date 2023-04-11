---
title: ProductRefiner.ThresholdValues Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ThresholdValues Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.ThresholdValues
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefiner.thresholdvalues(v=AX.60)
ms:contentKeyID: 65319791
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.ThresholdValues
dev_langs:
- CSharp
- C++
- VB
---

# ThresholdValues Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the encoded string of threshold values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("THRESHOLDVALUE")> _
Public Property ThresholdValues As String
    Get
    Set
'Usage
Dim instance As ProductRefiner
Dim value As String

value = instance.ThresholdValues

instance.ThresholdValues = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("THRESHOLDVALUE")]
public string ThresholdValues { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"THRESHOLDVALUE")]
public:
property String^ ThresholdValues {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductRefiner Class](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

