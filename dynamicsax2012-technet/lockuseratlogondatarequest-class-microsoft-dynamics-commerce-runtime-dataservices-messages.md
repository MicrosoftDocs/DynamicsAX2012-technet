---
title: LockUserAtLogOnDataRequest Class (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: LockUserAtLogOnDataRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.LockUserAtLogOnDataRequest
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.lockuseratlogondatarequest(v=AX.60)
ms:contentKeyID: 65321514
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.LockUserAtLogOnDataRequest
dev_langs:
- CSharp
- C++
- VB
---

# LockUserAtLogOnDataRequest Class

Request to lock the current user, so that same user can't log into another terminal until log off from the current terminal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public NotInheritable Class LockUserAtLogOnDataRequest _
    Inherits UnLockUserAtLogOffDataRequest
'Usage
Dim instance As LockUserAtLogOnDataRequest
```

``` csharp
[DataContractAttribute]
public sealed class LockUserAtLogOnDataRequest : UnLockUserAtLogOffDataRequest
```

``` c++
[DataContractAttribute]
public ref class LockUserAtLogOnDataRequest sealed : public UnLockUserAtLogOffDataRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DataRequest](datarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UnLockUserAtLogOffDataRequest](unlockuseratlogoffdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.LockUserAtLogOnDataRequest  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

