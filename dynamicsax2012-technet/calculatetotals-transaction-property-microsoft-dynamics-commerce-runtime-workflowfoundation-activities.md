---
title: CalculateTotals.Transaction Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: Transaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.CalculateTotals.Transaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.calculatetotals.transaction(v=AX.60)
ms:contentKeyID: 65323019
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.CalculateTotals.Transaction
dev_langs:
- CSharp
- C++
- VB
---

# Transaction Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property Transaction As OutArgument(Of SalesTransaction)
    Get
    Set
'Usage
Dim instance As CalculateTotals
Dim value As OutArgument(Of SalesTransaction)

value = instance.Transaction

instance.Transaction = value
```

``` csharp
public OutArgument<SalesTransaction> Transaction { get; set; }
```

``` c++
public:
property OutArgument<SalesTransaction^>^ Transaction {
    OutArgument<SalesTransaction^>^ get ();
    void set (OutArgument<SalesTransaction^>^ value);
}
```

#### Property Value

Type: OutArgument\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns OutArgument.  

## See Also

#### Reference

[CalculateTotals Class](calculatetotals-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

