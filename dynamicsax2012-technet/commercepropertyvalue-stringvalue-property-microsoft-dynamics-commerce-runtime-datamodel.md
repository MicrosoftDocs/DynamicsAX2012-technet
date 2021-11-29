---
title: CommercePropertyValue.StringValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StringValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.StringValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.stringvalue(v=AX.60)
ms:contentKeyID: 62202481
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.StringValue
dev_langs:
- CSharp
- C++
- VB
---

# StringValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the StringValue for the property, dependant on propertyType.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StringValue As String
    Get
    Set
'Usage
Dim instance As CommercePropertyValue
Dim value As String

value = instance.StringValue

instance.StringValue = value
```

``` csharp
[DataMemberAttribute]
public string StringValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ StringValue {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Private setter should be used by deserializer only.

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

