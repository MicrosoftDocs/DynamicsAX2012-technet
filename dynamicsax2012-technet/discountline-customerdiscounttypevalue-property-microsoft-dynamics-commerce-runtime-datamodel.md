---
title: DiscountLine.CustomerDiscountTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerDiscountTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.CustomerDiscountTypeValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.customerdiscounttypevalue(v=AX.60)
ms:contentKeyID: 62212594
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.CustomerDiscountTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# CustomerDiscountTypeValue Property

Gets or sets the value of the customer discount type enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerDiscountTypeValue As Integer
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As Integer

value = instance.CustomerDiscountTypeValue

instance.CustomerDiscountTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int CustomerDiscountTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int CustomerDiscountTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

