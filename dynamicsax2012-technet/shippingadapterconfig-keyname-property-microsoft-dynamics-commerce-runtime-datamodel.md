---
title: ShippingAdapterConfig.KeyName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KeyName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingAdapterConfig.KeyName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shippingadapterconfig.keyname(v=AX.60)
ms:contentKeyID: 49822646
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingAdapterConfig.KeyName
dev_langs:
- CSharp
- C++
- VB
---

# KeyName Property

Gets the name of the key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("KEYNAME")> _
<DataMemberAttribute> _
Public Property KeyName As String
    Get
    Friend Set
'Usage
Dim instance As ShippingAdapterConfig
Dim value As String

value = instance.KeyName
```

``` csharp
[ColumnAttribute("KEYNAME")]
[DataMemberAttribute]
public string KeyName { get; internal set; }
```

``` c++
[ColumnAttribute(L"KEYNAME")]
[DataMemberAttribute]
public:
property String^ KeyName {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShippingAdapterConfig Class](shippingadapterconfig-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

