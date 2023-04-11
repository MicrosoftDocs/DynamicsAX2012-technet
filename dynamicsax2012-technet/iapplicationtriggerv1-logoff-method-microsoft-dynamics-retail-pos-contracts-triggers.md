---
title: IApplicationTriggerV1.Logoff Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: Logoff Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IApplicationTriggerV1.Logoff(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iapplicationtriggerv1.logoff(v=AX.60)
ms:contentKeyID: 47129231
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IApplicationTriggerV1.Logoff
dev_langs:
- CSharp
- C++
- VB
---

# Logoff Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggers when the logoff operation is run.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub Logoff ( _
    operatorId As String, _
    name As String _
)
'Usage
Dim instance As IApplicationTriggerV1
Dim operatorId As String
Dim name As String

instance.Logoff(operatorId, name)
```

``` csharp
void Logoff(
    string operatorId,
    string name
)
```

``` c++
void Logoff(
    String^ operatorId, 
    String^ name
)
```

#### Parameters

  - operatorId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IApplicationTriggerV1 Interface](iapplicationtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

