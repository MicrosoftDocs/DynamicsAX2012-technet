---
title: ChannelProperty.Value Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProperty.Value
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelproperty.value(v=AX.60)
ms:contentKeyID: 49838289
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProperty.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property

Gets or sets the property value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALUE")> _
<DataMemberAttribute> _
Public Property Value As String
    Get
    Set
'Usage
Dim instance As ChannelProperty
Dim value As String

value = instance.Value

instance.Value = value
```

``` csharp
[ColumnAttribute("VALUE")]
[DataMemberAttribute]
public string Value { get; set; }
```

``` c++
[ColumnAttribute(L"VALUE")]
[DataMemberAttribute]
public:
property String^ Value {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The property value.  

## See Also

#### Reference

[ChannelProperty Class](channelproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

