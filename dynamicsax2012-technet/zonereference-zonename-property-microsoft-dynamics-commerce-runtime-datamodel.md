---
title: ZoneReference.ZoneName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ZoneName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ZoneReference.ZoneName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.zonereference.zonename(v=AX.60)
ms:contentKeyID: 62205534
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ZoneReference.ZoneName
dev_langs:
- CSharp
- C++
- VB
---

# ZoneName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of zone name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ZONENAME")> _
Public Property ZoneName As String
    Get
    Set
'Usage
Dim instance As ZoneReference
Dim value As String

value = instance.ZoneName

instance.ZoneName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ZONENAME")]
public string ZoneName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ZONENAME")]
public:
property String^ ZoneName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The zone name.  

## See Also

#### Reference

[ZoneReference Class](zonereference-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

