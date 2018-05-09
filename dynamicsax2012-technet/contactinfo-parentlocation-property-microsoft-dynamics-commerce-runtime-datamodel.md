---
title: ContactInfo.ParentLocation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ParentLocation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.ParentLocation
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.contactinfo.parentlocation(v=AX.60)
ms:contentKeyID: 62212993
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.ParentLocation
dev_langs:
- CSharp
- C++
- VB
---

# ParentLocation Property

Gets or sets the parent location.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PARENTLOCATION")> _
<DataMemberAttribute> _
Public Property ParentLocation As Long
    Get
    Set
'Usage
Dim instance As ContactInfo
Dim value As Long

value = instance.ParentLocation

instance.ParentLocation = value
```

``` csharp
[ColumnAttribute("PARENTLOCATION")]
[DataMemberAttribute]
public long ParentLocation { get; set; }
```

``` c++
[ColumnAttribute(L"PARENTLOCATION")]
[DataMemberAttribute]
public:
property long long ParentLocation {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The parent location.  

## See Also

#### Reference

[ContactInfo Class](contactinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

