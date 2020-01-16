---
title: DiscountCode.Barcode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Barcode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.Barcode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountcode.barcode(v=AX.60)
ms:contentKeyID: 49826697
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.Barcode
dev_langs:
- CSharp
- C++
- VB
---

# Barcode Property

Gets or sets the barcode string associated with this discount code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("BARCODE")> _
<DataMemberAttribute> _
Public Property Barcode As String
    Get
    Set
'Usage
Dim instance As DiscountCode
Dim value As String

value = instance.Barcode

instance.Barcode = value
```

``` csharp
[ColumnAttribute("BARCODE")]
[DataMemberAttribute]
public string Barcode { get; set; }
```

``` c++
[ColumnAttribute(L"BARCODE")]
[DataMemberAttribute]
public:
property String^ Barcode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DiscountCode Class](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

