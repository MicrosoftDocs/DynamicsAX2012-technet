---
title: Address.IsPrivate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsPrivate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.IsPrivate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.address.isprivate(v=AX.60)
ms:contentKeyID: 62206129
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.IsPrivate
dev_langs:
- CSharp
- C++
- VB
---

# IsPrivate Property

Gets or sets a value indicating whether this Address is the private address or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISPRIVATE")> _
Public Property IsPrivate As Boolean
    Get
    Set
'Usage
Dim instance As Address
Dim value As Boolean

value = instance.IsPrivate

instance.IsPrivate = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISPRIVATE")]
public bool IsPrivate { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISPRIVATE")]
public:
property bool IsPrivate {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
The IsPrivate.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

