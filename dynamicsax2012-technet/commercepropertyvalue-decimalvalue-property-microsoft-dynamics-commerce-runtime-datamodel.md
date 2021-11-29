---
title: CommercePropertyValue.DecimalValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DecimalValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.DecimalValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.decimalvalue(v=AX.60)
ms:contentKeyID: 62202584
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.DecimalValue
dev_langs:
- CSharp
- C++
- VB
---

# DecimalValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the DecimalValue for the property, dependant on propertyType.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DecimalValue As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As CommercePropertyValue
Dim value As Nullable(Of Decimal)

value = instance.DecimalValue

instance.DecimalValue = value
```

``` csharp
[DataMemberAttribute]
public Nullable<decimal> DecimalValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<Decimal> DecimalValue {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## Remarks

Private setter should be used by deserializer only.

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

