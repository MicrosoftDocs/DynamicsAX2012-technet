---
title: OrgUnitContact.ContactType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ContactType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitContact.ContactType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitcontact.contacttype(v=AX.60)
ms:contentKeyID: 62211128
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitContact.ContactType
dev_langs:
- CSharp
- C++
- VB
---

# ContactType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the address type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property ContactType As ContactInfoType
    Get
    Friend Set
'Usage
Dim instance As OrgUnitContact
Dim value As ContactInfoType

value = instance.ContactType
```

``` csharp
public ContactInfoType ContactType { get; internal set; }
```

``` c++
public:
property ContactInfoType ContactType {
    ContactInfoType get ();
    internal: void set (ContactInfoType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfoType](contactinfotype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ContactInfoType](contactinfotype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[OrgUnitContact Class](orgunitcontact-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

