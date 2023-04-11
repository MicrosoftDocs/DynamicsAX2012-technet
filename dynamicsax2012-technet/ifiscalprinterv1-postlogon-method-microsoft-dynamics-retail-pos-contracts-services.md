---
title: IFiscalPrinterV1.PostLogOn Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PostLogOn Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PostLogOn(System.Boolean,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.postlogon(v=AX.60)
ms:contentKeyID: 62203689
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PostLogOn
dev_langs:
- CSharp
- C++
- VB
---

# PostLogOn Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggers after the login operation has been executed.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostLogOn ( _
    logOnSuccessful As Boolean, _
    operatorId As String, _
    name As String _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim logOnSuccessful As Boolean
Dim operatorId As String
Dim name As String

instance.PostLogOn(logOnSuccessful, operatorId, _
    name)
```

``` csharp
void PostLogOn(
    bool logOnSuccessful,
    string operatorId,
    string name
)
```

``` c++
void PostLogOn(
    bool logOnSuccessful, 
    String^ operatorId, 
    String^ name
)
```

#### Parameters

  - logOnSuccessful  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - operatorId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

