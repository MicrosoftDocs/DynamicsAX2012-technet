---
title: Address.AttentionTo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AttentionTo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.AttentionTo
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.address.attentionto(v=AX.60)
ms:contentKeyID: 62214442
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.AttentionTo
dev_langs:
- CSharp
- C++
- VB
---

# AttentionTo Property

Gets or sets the AttentionTo field.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ATTENTIONTOADDRESSLINE")> _
<DataMemberAttribute> _
Public Property AttentionTo As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.AttentionTo

instance.AttentionTo = value
```

``` csharp
[ColumnAttribute("ATTENTIONTOADDRESSLINE")]
[DataMemberAttribute]
public string AttentionTo { get; set; }
```

``` c++
[ColumnAttribute(L"ATTENTIONTOADDRESSLINE")]
[DataMemberAttribute]
public:
property String^ AttentionTo {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The AttentionTo.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

