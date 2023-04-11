---
title: ISCJournalTransactionV1.Message Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Message Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISCJournalTransactionV1.Message
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iscjournaltransactionv1.message(v=AX.60)
ms:contentKeyID: 47344314
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISCJournalTransactionV1.Message
dev_langs:
- CSharp
- C++
- VB
---

# Message Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Message As String
    Get
    Set
'Usage
Dim instance As ISCJournalTransactionV1
Dim value As String

value = instance.Message

instance.Message = value
```

``` csharp
string Message { get; set; }
```

``` c++
property String^ Message {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) string.  

## See Also

#### Reference

[ISCJournalTransactionV1 Interface](iscjournaltransactionv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

