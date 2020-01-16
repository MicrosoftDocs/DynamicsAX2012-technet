---
title: CommercePropertyValue.DateTimeOffsetValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DateTimeOffsetValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.DateTimeOffsetValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.datetimeoffsetvalue(v=AX.60)
ms:contentKeyID: 62206085
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.DateTimeOffsetValue
dev_langs:
- CSharp
- C++
- VB
---

# DateTimeOffsetValue Property

Gets the DateTimeOffsetValue for the property, dependant on propertyType.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DateTimeOffsetValue As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As CommercePropertyValue
Dim value As Nullable(Of DateTimeOffset)

value = instance.DateTimeOffsetValue

instance.DateTimeOffsetValue = value
```

``` csharp
[DataMemberAttribute]
public Nullable<DateTimeOffset> DateTimeOffsetValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<DateTimeOffset> DateTimeOffsetValue {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## Remarks

Private setter should be used by deserializer only.

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

