---
title: OrgUnit.Latitude Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Latitude Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.Latitude
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit.latitude(v=AX.60)
ms:contentKeyID: 65322332
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.Latitude
dev_langs:
- CSharp
- C++
- VB
---

# Latitude Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LATITUDE")> _
<DataMemberAttribute> _
Public Property Latitude As Decimal
    Get
    Set
'Usage
Dim instance As OrgUnit
Dim value As Decimal

value = instance.Latitude

instance.Latitude = value
```

``` csharp
[ColumnAttribute("LATITUDE")]
[DataMemberAttribute]
public decimal Latitude { get; set; }
```

``` c++
[ColumnAttribute(L"LATITUDE")]
[DataMemberAttribute]
public:
property Decimal Latitude {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[OrgUnit Class](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

