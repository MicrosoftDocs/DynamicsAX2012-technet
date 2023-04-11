---
title: Address.StateName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StateName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.StateName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.statename(v=AX.60)
ms:contentKeyID: 65318799
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.StateName
dev_langs:
- CSharp
- C++
- VB
---

# StateName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STATENAME")> _
<DataMemberAttribute> _
Public Property StateName As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.StateName

instance.StateName = value
```

``` csharp
[ColumnAttribute("STATENAME")]
[DataMemberAttribute]
public string StateName { get; set; }
```

``` c++
[ColumnAttribute(L"STATENAME")]
[DataMemberAttribute]
public:
property String^ StateName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

