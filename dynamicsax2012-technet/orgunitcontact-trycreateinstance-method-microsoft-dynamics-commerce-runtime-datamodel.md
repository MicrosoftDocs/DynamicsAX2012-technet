---
title: OrgUnitContact.TryCreateInstance Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TryCreateInstance Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitContact.TryCreateInstance(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitcontact.trycreateinstance(v=AX.60)
ms:contentKeyID: 62209947
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitContact.TryCreateInstance
dev_langs:
- CSharp
- C++
- VB
---

# TryCreateInstance Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Try create instance of the[OrgUnitContact](orgunitcontact-class-microsoft-dynamics-commerce-runtime-datamodel.md) out of the [CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md).

Returns null if required fields are missing without failing.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function TryCreateInstance ( _
    entity As CommerceEntity _
) As OrgUnitContact
'Usage
Dim entity As CommerceEntity
Dim returnValue As OrgUnitContact

returnValue = OrgUnitContact.TryCreateInstance(entity)
```

``` csharp
public static OrgUnitContact TryCreateInstance(
    CommerceEntity entity
)
```

``` c++
public:
static OrgUnitContact^ TryCreateInstance(
    CommerceEntity^ entity
)
```

#### Parameters

  - entity  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitContact](orgunitcontact-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Instance of the [OrgUnitContact](orgunitcontact-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[OrgUnitContact Class](orgunitcontact-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

