---
title: Address.City Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: City Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.City
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.city(v=AX.60)
ms:contentKeyID: 49830761
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.City
dev_langs:
- CSharp
- C++
- VB
---

# City Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the City.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CITY")> _
<DataMemberAttribute> _
Public Property City As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.City

instance.City = value
```

``` csharp
[ColumnAttribute("CITY")]
[DataMemberAttribute]
public string City { get; set; }
```

``` c++
[ColumnAttribute(L"CITY")]
[DataMemberAttribute]
public:
property String^ City {
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

