---
title: ZoneReference.ZoneId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ZoneId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ZoneReference.ZoneId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.zonereference.zoneid(v=AX.60)
ms:contentKeyID: 62207069
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ZoneReference.ZoneId
dev_langs:
- CSharp
- C++
- VB
---

# ZoneId Property

Gets or sets the value of zone identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ZONEID")> _
<DataMemberAttribute> _
Public Property ZoneId As String
    Get
    Set
'Usage
Dim instance As ZoneReference
Dim value As String

value = instance.ZoneId

instance.ZoneId = value
```

``` csharp
[ColumnAttribute("ZONEID")]
[DataMemberAttribute]
public string ZoneId { get; set; }
```

``` c++
[ColumnAttribute(L"ZONEID")]
[DataMemberAttribute]
public:
property String^ ZoneId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The zone identifier.  

## See Also

#### Reference

[ZoneReference Class](zonereference-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

