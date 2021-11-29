---
title: IDialogV1.ShowJournalDialog Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ShowJournalDialog Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.ShowJournalDialog(Microsoft.Dynamics.Retail.Pos.Contracts.Services.JournalDialogResults@,System.Object@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idialogv1.showjournaldialog(v=AX.60)
ms:contentKeyID: 47343838
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.ShowJournalDialog
dev_langs:
- CSharp
- C++
- VB
---

# ShowJournalDialog Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Shows journal dialog.

Displays a dialog box listing journal transactions.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ShowJournalDialog ( _
    ByRef journalDialogResults As JournalDialogResults, _
    ByRef dialogResultObject As Object, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IDialogV1
Dim journalDialogResults As JournalDialogResults
Dim dialogResultObject As Object
Dim posTransaction As IPosTransaction

instance.ShowJournalDialog(journalDialogResults, _
    dialogResultObject, posTransaction)
```

``` csharp
void ShowJournalDialog(
    ref JournalDialogResults journalDialogResults,
    ref Object dialogResultObject,
    IPosTransaction posTransaction
)
```

``` c++
void ShowJournalDialog(
    JournalDialogResults% journalDialogResults, 
    Object^% dialogResultObject, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - journalDialogResults  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.JournalDialogResults](journaldialogresults-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - dialogResultObject  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IDialogV1 Interface](idialogv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

