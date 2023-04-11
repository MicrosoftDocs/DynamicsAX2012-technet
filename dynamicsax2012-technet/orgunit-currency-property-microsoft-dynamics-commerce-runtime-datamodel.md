---
title: OrgUnit.Currency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Currency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.Currency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit.currency(v=AX.60)
ms:contentKeyID: 62207858
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.Currency
dev_langs:
- CSharp
- C++
- VB
---

# Currency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the currency of a organization unit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CURRENCY")> _
<DataMemberAttribute> _
Public Property Currency As String
    Get
    Set
'Usage
Dim instance As OrgUnit
Dim value As String

value = instance.Currency

instance.Currency = value
```

``` csharp
[ColumnAttribute("CURRENCY")]
[DataMemberAttribute]
public string Currency { get; set; }
```

``` c++
[ColumnAttribute(L"CURRENCY")]
[DataMemberAttribute]
public:
property String^ Currency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnit Class](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

