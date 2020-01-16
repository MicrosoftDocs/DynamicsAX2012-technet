---
title: DiscountCode.IsEnabled Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsEnabled Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.IsEnabled
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountcode.isenabled(v=AX.60)
ms:contentKeyID: 62210555
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.IsEnabled
dev_langs:
- CSharp
- C++
- VB
---

# IsEnabled Property

Gets or sets a value indicating whether this [DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md) is enabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STATUS")> _
Public Property IsEnabled As Boolean
    Get
    Set
'Usage
Dim instance As DiscountCode
Dim value As Boolean

value = instance.IsEnabled

instance.IsEnabled = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STATUS")]
public bool IsEnabled { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STATUS")]
public:
property bool IsEnabled {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[DiscountCode Class](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

