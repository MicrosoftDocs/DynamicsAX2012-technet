---
title: DiscountCode.IsDiscountCodeRequired Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsDiscountCodeRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.IsDiscountCodeRequired
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.discountcode.isdiscountcoderequired(v=AX.60)
ms:contentKeyID: 62211993
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.IsDiscountCodeRequired
dev_langs:
- CSharp
- C++
- VB
---

# IsDiscountCodeRequired Property

Gets or sets a value indicating whether the discount code is required.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISDISCOUNTCODEREQUIRED")> _
<DataMemberAttribute> _
Public Property IsDiscountCodeRequired As Boolean
    Get
    Set
'Usage
Dim instance As DiscountCode
Dim value As Boolean

value = instance.IsDiscountCodeRequired

instance.IsDiscountCodeRequired = value
```

``` csharp
[ColumnAttribute("ISDISCOUNTCODEREQUIRED")]
[DataMemberAttribute]
public bool IsDiscountCodeRequired { get; set; }
```

``` c++
[ColumnAttribute(L"ISDISCOUNTCODEREQUIRED")]
[DataMemberAttribute]
public:
property bool IsDiscountCodeRequired {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[DiscountCode Class](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

