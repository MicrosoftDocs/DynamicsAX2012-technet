---
title: ChannelCategoryAttribute.IntegerValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IntegerValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.IntegerValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelcategoryattribute.integervalue(v=AX.60)
ms:contentKeyID: 65320634
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.IntegerValue
dev_langs:
- CSharp
- C++
- VB
---

# IntegerValue Property

Gets the integer value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INTVALUE")> _
Public ReadOnly Property IntegerValue As Integer
    Get
'Usage
Dim instance As ChannelCategoryAttribute
Dim value As Integer

value = instance.IntegerValue
```

``` csharp
[ColumnAttribute("INTVALUE")]
public int IntegerValue { get; }
```

``` c++
[ColumnAttribute(L"INTVALUE")]
public:
property int IntegerValue {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ChannelCategoryAttribute Class](channelcategoryattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

