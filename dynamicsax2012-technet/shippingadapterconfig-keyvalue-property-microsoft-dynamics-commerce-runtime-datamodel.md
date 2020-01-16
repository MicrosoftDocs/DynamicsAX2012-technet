---
title: ShippingAdapterConfig.KeyValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KeyValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingAdapterConfig.KeyValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shippingadapterconfig.keyvalue(v=AX.60)
ms:contentKeyID: 49827173
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingAdapterConfig.KeyValue
dev_langs:
- CSharp
- C++
- VB
---

# KeyValue Property

Gets the key value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("KEYVALUE")> _
<DataMemberAttribute> _
Public Property KeyValue As String
    Get
    Friend Set
'Usage
Dim instance As ShippingAdapterConfig
Dim value As String

value = instance.KeyValue
```

``` csharp
[ColumnAttribute("KEYVALUE")]
[DataMemberAttribute]
public string KeyValue { get; internal set; }
```

``` c++
[ColumnAttribute(L"KEYVALUE")]
[DataMemberAttribute]
public:
property String^ KeyValue {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShippingAdapterConfig Class](shippingadapterconfig-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

