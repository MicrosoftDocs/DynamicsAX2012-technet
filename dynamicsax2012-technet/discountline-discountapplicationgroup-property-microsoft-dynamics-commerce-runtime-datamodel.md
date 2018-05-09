---
title: DiscountLine.DiscountApplicationGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountApplicationGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.DiscountApplicationGroup
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.discountapplicationgroup(v=AX.60)
ms:contentKeyID: 49853262
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.DiscountApplicationGroup
dev_langs:
- CSharp
- C++
- VB
---

# DiscountApplicationGroup Property

Gets or sets the unique group id for this application of the offer

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountApplicationGroup As String
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As String

value = instance.DiscountApplicationGroup

instance.DiscountApplicationGroup = value
```

``` csharp
[DataMemberAttribute]
public string DiscountApplicationGroup { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DiscountApplicationGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

This is used by the concurrency code to know which discount lines across the transaction must be applied as a unit.

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

