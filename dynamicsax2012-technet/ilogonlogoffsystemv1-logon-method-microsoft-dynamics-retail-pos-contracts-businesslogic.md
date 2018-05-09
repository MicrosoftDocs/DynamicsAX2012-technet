---
title: ILogonLogoffSystemV1.LogOn Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: LogOn Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ILogonLogoffSystemV1.LogOn(System.String,System.String,System.String,System.String,System.String@,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.ilogonlogoffsystemv1.logon(v=AX.60)
ms:contentKeyID: 47129152
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ILogonLogoffSystemV1.LogOn
dev_langs:
- CSharp
- C++
- VB
---

# LogOn Method

Attempts to Log in to the POS application.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function LogOn ( _
    operatorId As String, _
    passwordHash As String, _
    name As String, _
    nameOnReceipt As String, _
    ByRef comment As String, _
    usePassword As Boolean _
) As Boolean
'Usage
Dim instance As ILogonLogoffSystemV1
Dim operatorId As String
Dim passwordHash As String
Dim name As String
Dim nameOnReceipt As String
Dim comment As String
Dim usePassword As Boolean
Dim returnValue As Boolean

returnValue = instance.LogOn(operatorId, _
    passwordHash, name, nameOnReceipt, _
    comment, usePassword)
```

``` csharp
bool LogOn(
    string operatorId,
    string passwordHash,
    string name,
    string nameOnReceipt,
    ref string comment,
    bool usePassword
)
```

``` c++
bool LogOn(
    String^ operatorId, 
    String^ passwordHash, 
    String^ name, 
    String^ nameOnReceipt, 
    String^% comment, 
    bool usePassword
)
```

#### Parameters

  - operatorId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - passwordHash  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - nameOnReceipt  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - usePassword  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true on success  

## See Also

#### Reference

[ILogonLogoffSystemV1 Interface](ilogonlogoffsystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

