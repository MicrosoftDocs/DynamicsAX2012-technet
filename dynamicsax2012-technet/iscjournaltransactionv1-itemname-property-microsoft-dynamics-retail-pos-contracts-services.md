---
title: ISCJournalTransactionV1.ItemName Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ItemName Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISCJournalTransactionV1.ItemName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iscjournaltransactionv1.itemname(v=AX.60)
ms:contentKeyID: 47344281
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISCJournalTransactionV1.ItemName
dev_langs:
- CSharp
- C++
- VB
---

# ItemName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ItemName As String
    Get
    Set
'Usage
Dim instance As ISCJournalTransactionV1
Dim value As String

value = instance.ItemName

instance.ItemName = value
```

``` csharp
string ItemName { get; set; }
```

``` c++
property String^ ItemName {
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

