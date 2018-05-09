---
title: CommercePropertyValue.IntegerValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IntegerValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.IntegerValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.integervalue(v=AX.60)
ms:contentKeyID: 62208839
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.IntegerValue
dev_langs:
- CSharp
- C++
- VB
---

# IntegerValue Property

Gets the IntegerValue for the property, dependant on propertyType.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IntegerValue As Nullable(Of Integer)
    Get
    Set
'Usage
Dim instance As CommercePropertyValue
Dim value As Nullable(Of Integer)

value = instance.IntegerValue

instance.IntegerValue = value
```

``` csharp
[DataMemberAttribute]
public Nullable<int> IntegerValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<int> IntegerValue {
    Nullable<int> get ();
    void set (Nullable<int> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\)).  

## Remarks

Private setter should be used by deserializer only.

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

