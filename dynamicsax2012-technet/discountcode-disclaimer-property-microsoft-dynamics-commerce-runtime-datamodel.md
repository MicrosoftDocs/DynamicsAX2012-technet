---
title: DiscountCode.Disclaimer Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Disclaimer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.Disclaimer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountcode.disclaimer(v=AX.60)
ms:contentKeyID: 62214714
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.Disclaimer
dev_langs:
- CSharp
- C++
- VB
---

# Disclaimer Property

Gets or sets the disclaimer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISCLAIMER")> _
<DataMemberAttribute> _
Public Property Disclaimer As String
    Get
    Set
'Usage
Dim instance As DiscountCode
Dim value As String

value = instance.Disclaimer

instance.Disclaimer = value
```

``` csharp
[ColumnAttribute("DISCLAIMER")]
[DataMemberAttribute]
public string Disclaimer { get; set; }
```

``` c++
[ColumnAttribute(L"DISCLAIMER")]
[DataMemberAttribute]
public:
property String^ Disclaimer {
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

