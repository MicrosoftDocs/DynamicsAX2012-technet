---
title: DiscountLine.IsDiscountCodeRequired Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsDiscountCodeRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.IsDiscountCodeRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.isdiscountcoderequired(v=AX.60)
ms:contentKeyID: 62212040
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.IsDiscountCodeRequired
dev_langs:
- CSharp
- C++
- VB
---

# IsDiscountCodeRequired Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether discount code is required for discount to be applied.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsDiscountCodeRequired As Boolean
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As Boolean

value = instance.IsDiscountCodeRequired

instance.IsDiscountCodeRequired = value
```

``` csharp
[DataMemberAttribute]
public bool IsDiscountCodeRequired { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsDiscountCodeRequired {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

