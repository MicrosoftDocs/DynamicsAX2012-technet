---
title: Cart.TaxOverrideCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxOverrideCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TaxOverrideCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.taxoverridecode(v=AX.60)
ms:contentKeyID: 62208955
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TaxOverrideCode
dev_langs:
- CSharp
- C++
- VB
---

# TaxOverrideCode Property

Gets or sets the tax override.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TaxOverrideCode As String
    Get
    Set
'Usage
Dim instance As Cart
Dim value As String

value = instance.TaxOverrideCode

instance.TaxOverrideCode = value
```

``` csharp
[DataMemberAttribute]
public string TaxOverrideCode { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TaxOverrideCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The tax override code.  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

