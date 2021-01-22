---
title: Address.Street Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Street Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.Street
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.street(v=AX.60)
ms:contentKeyID: 49850354
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.Street
dev_langs:
- CSharp
- C++
- VB
---

# Street Property

Gets or sets the Street.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STREET")> _
Public Property Street As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.Street

instance.Street = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STREET")]
public string Street { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STREET")]
public:
property String^ Street {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

