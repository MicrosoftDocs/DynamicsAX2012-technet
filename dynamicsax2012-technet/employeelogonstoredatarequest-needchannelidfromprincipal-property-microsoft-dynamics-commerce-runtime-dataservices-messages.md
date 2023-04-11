---
title: EmployeeLogOnStoreDataRequest.NeedChannelIdFromPrincipal Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: NeedChannelIdFromPrincipal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeeLogOnStoreDataRequest.NeedChannelIdFromPrincipal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.employeelogonstoredatarequest.needchannelidfromprincipal(v=AX.60)
ms:contentKeyID: 65320976
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeeLogOnStoreDataRequest.NeedChannelIdFromPrincipal
dev_langs:
- CSharp
- C++
- VB
---

# NeedChannelIdFromPrincipal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the channel should be retrieved from principal for the specific request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overrides ReadOnly Property NeedChannelIdFromPrincipal As Boolean
    Get
'Usage
Dim instance As EmployeeLogOnStoreDataRequest
Dim value As Boolean

value = instance.NeedChannelIdFromPrincipal
```

``` csharp
[IgnoreDataMemberAttribute]
public override bool NeedChannelIdFromPrincipal { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
virtual property bool NeedChannelIdFromPrincipal {
    bool get () override;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[EmployeeLogOnStoreDataRequest Class](employeelogonstoredatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

