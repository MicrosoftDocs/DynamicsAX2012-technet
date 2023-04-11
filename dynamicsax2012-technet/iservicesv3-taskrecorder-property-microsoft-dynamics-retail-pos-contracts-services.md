---
title: IServicesV3.TaskRecorder Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: TaskRecorder Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV3.TaskRecorder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iservicesv3.taskrecorder(v=AX.60)
ms:contentKeyID: 62202892
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV3.TaskRecorder
dev_langs:
- CSharp
- C++
- VB
---

# TaskRecorder Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Task recorder service

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TaskRecorder As ITaskRecorder
    Get
'Usage
Dim instance As IServicesV3
Dim value As ITaskRecorder

value = instance.TaskRecorder
```

``` csharp
ITaskRecorder TaskRecorder { get; }
```

``` c++
property ITaskRecorder^ TaskRecorder {
    ITaskRecorder^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITaskRecorder](itaskrecorder-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [ITaskRecorder](itaskrecorder-interface-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[IServicesV3 Interface](iservicesv3-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

