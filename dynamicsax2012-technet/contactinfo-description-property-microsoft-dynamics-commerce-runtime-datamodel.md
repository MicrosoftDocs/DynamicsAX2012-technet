---
title: ContactInfo.Description Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Description Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.Description
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.contactinfo.description(v=AX.60)
ms:contentKeyID: 62206871
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.Description
dev_langs:
- CSharp
- C++
- VB
---

# Description Property

Gets or sets the description.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LOCATIONDESCRIPTION")> _
<DataMemberAttribute> _
Public Property Description As String
    Get
    Set
'Usage
Dim instance As ContactInfo
Dim value As String

value = instance.Description

instance.Description = value
```

``` csharp
[ColumnAttribute("LOCATIONDESCRIPTION")]
[DataMemberAttribute]
public string Description { get; set; }
```

``` c++
[ColumnAttribute(L"LOCATIONDESCRIPTION")]
[DataMemberAttribute]
public:
property String^ Description {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The description.  

## See Also

#### Reference

[ContactInfo Class](contactinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

