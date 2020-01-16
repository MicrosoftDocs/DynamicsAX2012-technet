---
title: OrgUnitLocation.Contacts Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Contacts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.Contacts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.contacts(v=AX.60)
ms:contentKeyID: 62213925
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.Contacts
dev_langs:
- CSharp
- C++
- VB
---

# Contacts Property

Gets the collection of contacts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Contacts As Collection(Of OrgUnitContact)
    Get
    Private Set
'Usage
Dim instance As OrgUnitLocation
Dim value As Collection(Of OrgUnitContact)

value = instance.Contacts
```

``` csharp
[DataMemberAttribute]
public Collection<OrgUnitContact> Contacts { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<OrgUnitContact^>^ Contacts {
    Collection<OrgUnitContact^>^ get ();
    private: void set (Collection<OrgUnitContact^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[OrgUnitContact](orgunitcontact-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

