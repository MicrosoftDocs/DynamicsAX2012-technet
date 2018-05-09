---
title: ICashChangerV1.Logout Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Logout Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.Logout
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icashchangerv1.logout(v=AX.60)
ms:contentKeyID: 47343871
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.Logout
dev_langs:
- CSharp
- C++
- VB
---

# Logout Method

Used to log out user from cash changer device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Logout As Boolean
'Usage
Dim instance As ICashChangerV1
Dim returnValue As Boolean

returnValue = instance.Logout()
```

``` csharp
bool Logout()
```

``` c++
bool Logout()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if it is successful; otherwise, false.  

## See Also

#### Reference

[ICashChangerV1 Interface](icashchangerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

