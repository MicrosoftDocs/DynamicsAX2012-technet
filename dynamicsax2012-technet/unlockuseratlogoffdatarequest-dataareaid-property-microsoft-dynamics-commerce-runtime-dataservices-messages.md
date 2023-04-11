---
title: UnLockUserAtLogOffDataRequest.DataAreaId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: DataAreaId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UnLockUserAtLogOffDataRequest.DataAreaId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.unlockuseratlogoffdatarequest.dataareaid(v=AX.60)
ms:contentKeyID: 65321108
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UnLockUserAtLogOffDataRequest.DataAreaId
dev_langs:
- CSharp
- C++
- VB
---

# DataAreaId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the data area identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DataAreaId As String
    Get
    Private Set
'Usage
Dim instance As UnLockUserAtLogOffDataRequest
Dim value As String

value = instance.DataAreaId
```

``` csharp
[DataMemberAttribute]
public string DataAreaId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DataAreaId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The data area identifier.  

## See Also

#### Reference

[UnLockUserAtLogOffDataRequest Class](unlockuseratlogoffdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

