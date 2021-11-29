---
title: ICashChangerV1.Login Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Login Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.Login(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icashchangerv1.login(v=AX.60)
ms:contentKeyID: 47344027
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.Login
dev_langs:
- CSharp
- C++
- VB
---

# Login Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Registers the user who has on cash changer device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Login ( _
    terminalID As String, _
    operatorID As String _
) As Boolean
'Usage
Dim instance As ICashChangerV1
Dim terminalID As String
Dim operatorID As String
Dim returnValue As Boolean

returnValue = instance.Login(terminalID, _
    operatorID)
```

``` csharp
bool Login(
    string terminalID,
    string operatorID
)
```

``` c++
bool Login(
    String^ terminalID, 
    String^ operatorID
)
```

#### Parameters

  - terminalID  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - operatorID  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if it is successful; otherwise, false.  

## See Also

#### Reference

[ICashChangerV1 Interface](icashchangerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

