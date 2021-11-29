---
title: Product.Locale Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Locale Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.Locale
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.locale(v=AX.60)
ms:contentKeyID: 62208268
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.Locale
dev_langs:
- CSharp
- C++
- VB
---

# Locale Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the locale.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Locale As String
    Get
    Set
'Usage
Dim instance As Product
Dim value As String

value = instance.Locale

instance.Locale = value
```

``` csharp
[DataMemberAttribute]
public string Locale { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Locale {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The locale.  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

