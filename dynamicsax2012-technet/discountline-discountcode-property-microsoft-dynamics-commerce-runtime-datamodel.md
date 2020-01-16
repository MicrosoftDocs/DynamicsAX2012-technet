---
title: DiscountLine.DiscountCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.DiscountCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.discountcode(v=AX.60)
ms:contentKeyID: 49853090
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.DiscountCode
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCode Property

Gets or sets the discount code (if any) which activated this discount line

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISCOUNTCODE")> _
<DataMemberAttribute> _
Public Property DiscountCode As String
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As String

value = instance.DiscountCode

instance.DiscountCode = value
```

``` csharp
[ColumnAttribute("DISCOUNTCODE")]
[DataMemberAttribute]
public string DiscountCode { get; set; }
```

``` c++
[ColumnAttribute(L"DISCOUNTCODE")]
[DataMemberAttribute]
public:
property String^ DiscountCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

