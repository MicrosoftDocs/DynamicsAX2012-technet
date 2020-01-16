---
title: IApplicationTriggerV1.PostLogon Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostLogon Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IApplicationTriggerV1.PostLogon(System.Boolean,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iapplicationtriggerv1.postlogon(v=AX.60)
ms:contentKeyID: 47128448
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IApplicationTriggerV1.PostLogon
dev_langs:
- CSharp
- C++
- VB
---

# PostLogon Method

Triggers after the login operation has run.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostLogon ( _
    loginSuccessful As Boolean, _
    operatorId As String, _
    name As String _
)
'Usage
Dim instance As IApplicationTriggerV1
Dim loginSuccessful As Boolean
Dim operatorId As String
Dim name As String

instance.PostLogon(loginSuccessful, operatorId, _
    name)
```

``` csharp
void PostLogon(
    bool loginSuccessful,
    string operatorId,
    string name
)
```

``` c++
void PostLogon(
    bool loginSuccessful, 
    String^ operatorId, 
    String^ name
)
```

#### Parameters

  - loginSuccessful  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

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

