---
title: UnLockUserAtLogOffDataRequest.StaffId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: StaffId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UnLockUserAtLogOffDataRequest.StaffId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.unlockuseratlogoffdatarequest.staffid(v=AX.60)
ms:contentKeyID: 65323128
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UnLockUserAtLogOffDataRequest.StaffId
dev_langs:
- CSharp
- C++
- VB
---

# StaffId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the staff identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StaffId As String
    Get
    Private Set
'Usage
Dim instance As UnLockUserAtLogOffDataRequest
Dim value As String

value = instance.StaffId
```

``` csharp
[DataMemberAttribute]
public string StaffId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ StaffId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The staff identifier.  

## See Also

#### Reference

[UnLockUserAtLogOffDataRequest Class](unlockuseratlogoffdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

