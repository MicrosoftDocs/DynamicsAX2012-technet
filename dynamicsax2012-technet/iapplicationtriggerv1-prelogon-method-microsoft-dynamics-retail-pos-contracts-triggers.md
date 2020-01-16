---
title: IApplicationTriggerV1.PreLogon Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreLogon Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IApplicationTriggerV1.PreLogon(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iapplicationtriggerv1.prelogon(v=AX.60)
ms:contentKeyID: 47129359
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IApplicationTriggerV1.PreLogon
dev_langs:
- CSharp
- C++
- VB
---

# PreLogon Method

Triggers just before the login operation is run.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreLogon ( _
    preTriggerResult As IPreTriggerResult, _
    operatorId As String, _
    name As String _
)
'Usage
Dim instance As IApplicationTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim operatorId As String
Dim name As String

instance.PreLogon(preTriggerResult, operatorId, _
    name)
```

``` csharp
void PreLogon(
    IPreTriggerResult preTriggerResult,
    string operatorId,
    string name
)
```

``` c++
void PreLogon(
    IPreTriggerResult^ preTriggerResult, 
    String^ operatorId, 
    String^ name
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - operatorId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IApplicationTriggerV1 Interface](iapplicationtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

