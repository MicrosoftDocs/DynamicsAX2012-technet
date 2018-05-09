---
title: CommercePropertyValue.BooleanValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BooleanValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.BooleanValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.booleanvalue(v=AX.60)
ms:contentKeyID: 62214484
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.BooleanValue
dev_langs:
- CSharp
- C++
- VB
---

# BooleanValue Property

Gets the BooleanValue for the property, dependant on propertyType.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property BooleanValue As Nullable(Of Boolean)
    Get
    Set
'Usage
Dim instance As CommercePropertyValue
Dim value As Nullable(Of Boolean)

value = instance.BooleanValue

instance.BooleanValue = value
```

``` csharp
[DataMemberAttribute]
public Nullable<bool> BooleanValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<bool> BooleanValue {
    Nullable<bool> get ();
    void set (Nullable<bool> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\)).  

## Remarks

Private setter should be used by deserializer only.

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

