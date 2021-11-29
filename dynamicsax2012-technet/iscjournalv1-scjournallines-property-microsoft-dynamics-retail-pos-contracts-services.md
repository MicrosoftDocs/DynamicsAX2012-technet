---
title: ISCJournalV1.SCJournalLines Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SCJournalLines Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISCJournalV1.SCJournalLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iscjournalv1.scjournallines(v=AX.60)
ms:contentKeyID: 47344181
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISCJournalV1.SCJournalLines
dev_langs:
- CSharp
- C++
- VB
---

# SCJournalLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SCJournalLines As IList(Of ISCJournalTransaction)
    Get
    Set
'Usage
Dim instance As ISCJournalV1
Dim value As IList(Of ISCJournalTransaction)

value = instance.SCJournalLines

instance.SCJournalLines = value
```

``` csharp
IList<ISCJournalTransaction> SCJournalLines { get; set; }
```

``` c++
property IList<ISCJournalTransaction^>^ SCJournalLines {
    IList<ISCJournalTransaction^>^ get ();
    void set (IList<ISCJournalTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[ISCJournalTransaction](iscjournaltransaction-interface-microsoft-dynamics-retail-pos-contracts-services.md)\>  
The [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)) list.  

## See Also

#### Reference

[ISCJournalV1 Interface](iscjournalv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

