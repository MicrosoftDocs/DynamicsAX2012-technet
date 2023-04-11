---
title: EmployeeLogOnStoreDataRequest.PasswordHash Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: PasswordHash Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeeLogOnStoreDataRequest.PasswordHash
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.employeelogonstoredatarequest.passwordhash(v=AX.60)
ms:contentKeyID: 65321343
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeeLogOnStoreDataRequest.PasswordHash
dev_langs:
- CSharp
- C++
- VB
---

# PasswordHash Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets passwordHash for the user.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PasswordHash As String
    Get
    Private Set
'Usage
Dim instance As EmployeeLogOnStoreDataRequest
Dim value As String

value = instance.PasswordHash
```

``` csharp
[DataMemberAttribute]
public string PasswordHash { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ PasswordHash {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The passwordHash.  

## See Also

#### Reference

[EmployeeLogOnStoreDataRequest Class](employeelogonstoredatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

