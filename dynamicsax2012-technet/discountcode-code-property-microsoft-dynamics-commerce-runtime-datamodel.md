---
title: DiscountCode.Code Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Code Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.Code
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.discountcode.code(v=AX.60)
ms:contentKeyID: 49834239
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.Code
dev_langs:
- CSharp
- C++
- VB
---

# Code Property

Gets or sets the discount code which activates the offer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<KeyAttribute> _
<ColumnAttribute("DISCOUNTCODE")> _
<DataMemberAttribute> _
Public Property Code As String
    Get
    Set
'Usage
Dim instance As DiscountCode
Dim value As String

value = instance.Code

instance.Code = value
```

``` csharp
[KeyAttribute]
[ColumnAttribute("DISCOUNTCODE")]
[DataMemberAttribute]
public string Code { get; set; }
```

``` c++
[KeyAttribute]
[ColumnAttribute(L"DISCOUNTCODE")]
[DataMemberAttribute]
public:
property String^ Code {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DiscountCode Class](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

