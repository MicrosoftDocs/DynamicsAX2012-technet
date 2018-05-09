---
title: ChannelCategoryAttribute.FloatValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FloatValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.FloatValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelcategoryattribute.floatvalue(v=AX.60)
ms:contentKeyID: 65319421
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.FloatValue
dev_langs:
- CSharp
- C++
- VB
---

# FloatValue Property

Gets the float value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FLOATVALUE")> _
Public ReadOnly Property FloatValue As Decimal
    Get
'Usage
Dim instance As ChannelCategoryAttribute
Dim value As Decimal

value = instance.FloatValue
```

``` csharp
[ColumnAttribute("FLOATVALUE")]
public decimal FloatValue { get; }
```

``` c++
[ColumnAttribute(L"FLOATVALUE")]
public:
property Decimal FloatValue {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ChannelCategoryAttribute Class](channelcategoryattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

