---
title: EmployeeTimeRegistrationResponse.Stores Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Stores Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationResponse.Stores
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.employeetimeregistrationresponse.stores(v=AX.60)
ms:contentKeyID: 62212634
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationResponse.Stores
dev_langs:
- CSharp
- C++
- VB
---

# Stores Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the list of employee registered stores from address book.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Stores As ReadOnlyCollection(Of OrgUnit)
    Get
    Private Set
'Usage
Dim instance As EmployeeTimeRegistrationResponse
Dim value As ReadOnlyCollection(Of OrgUnit)

value = instance.Stores
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<OrgUnit> Stores { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<OrgUnit^>^ Stores {
    ReadOnlyCollection<OrgUnit^>^ get ();
    private: void set (ReadOnlyCollection<OrgUnit^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[EmployeeTimeRegistrationResponse Class](employeetimeregistrationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

