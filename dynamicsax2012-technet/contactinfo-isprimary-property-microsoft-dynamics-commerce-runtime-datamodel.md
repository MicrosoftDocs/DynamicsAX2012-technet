---
title: ContactInfo.IsPrimary Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsPrimary Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.IsPrimary
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.contactinfo.isprimary(v=AX.60)
ms:contentKeyID: 62211906
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.IsPrimary
dev_langs:
- CSharp
- C++
- VB
---

# IsPrimary Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether this contact is the primary contact or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISPRIMARY")> _
<DataMemberAttribute> _
Public Property IsPrimary As Boolean
    Get
    Set
'Usage
Dim instance As ContactInfo
Dim value As Boolean

value = instance.IsPrimary

instance.IsPrimary = value
```

``` csharp
[ColumnAttribute("ISPRIMARY")]
[DataMemberAttribute]
public bool IsPrimary { get; set; }
```

``` c++
[ColumnAttribute(L"ISPRIMARY")]
[DataMemberAttribute]
public:
property bool IsPrimary {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The IsPrimary.  

## See Also

#### Reference

[ContactInfo Class](contactinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

