---
title: CommercePropertyValue.ByteValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ByteValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.ByteValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.bytevalue(v=AX.60)
ms:contentKeyID: 62208327
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.ByteValue
dev_langs:
- CSharp
- C++
- VB
---

# ByteValue Property

Gets the ByteValue for the property, dependant on propertyType.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ByteValue As Nullable(Of Byte)
    Get
    Set
'Usage
Dim instance As CommercePropertyValue
Dim value As Nullable(Of Byte)

value = instance.ByteValue

instance.ByteValue = value
```

``` csharp
[DataMemberAttribute]
public Nullable<byte> ByteValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<unsigned char> ByteValue {
    Nullable<unsigned char> get ();
    void set (Nullable<unsigned char> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Byte](https://technet.microsoft.com/en-us/library/yyb1w04y\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\)).  

## Remarks

Private setter should be used by deserializer only.

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

