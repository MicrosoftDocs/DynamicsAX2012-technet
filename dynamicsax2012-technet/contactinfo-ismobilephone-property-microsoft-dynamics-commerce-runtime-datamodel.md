---
title: ContactInfo.IsMobilePhone Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsMobilePhone Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.IsMobilePhone
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.contactinfo.ismobilephone(v=AX.60)
ms:contentKeyID: 62207051
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.IsMobilePhone
dev_langs:
- CSharp
- C++
- VB
---

# IsMobilePhone Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether this instance is mobile phone.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISMOBILEPHONE")> _
Public Property IsMobilePhone As Boolean
    Get
    Set
'Usage
Dim instance As ContactInfo
Dim value As Boolean

value = instance.IsMobilePhone

instance.IsMobilePhone = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISMOBILEPHONE")]
public bool IsMobilePhone { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISMOBILEPHONE")]
public:
property bool IsMobilePhone {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if this instance is mobile phone; otherwise, false.  

## See Also

#### Reference

[ContactInfo Class](contactinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

