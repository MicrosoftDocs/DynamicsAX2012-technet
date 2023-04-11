---
title: ContactInfo Constructor (ContactInfoType, String) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ContactInfo Constructor (ContactInfoType, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfoType,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.contactinfo.contactinfo(v=AX.60)
ms:contentKeyID: 62214145
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ContactInfo Constructor (ContactInfoType, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ContactInfo](contactinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    type As ContactInfoType, _
    className As String _
)
'Usage
Dim type As ContactInfoType
Dim className As String

Dim instance As New ContactInfo(type, className)
```

``` csharp
public ContactInfo(
    ContactInfoType type,
    string className
)
```

``` c++
public:
ContactInfo(
    ContactInfoType type, 
    String^ className
)
```

#### Parameters

  - type  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfoType](contactinfotype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ContactInfo Class](contactinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ContactInfo Overload](contactinfo-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

