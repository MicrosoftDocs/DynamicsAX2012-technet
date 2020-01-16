---
title: CreateSalesTransaction.TransactionId Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: TransactionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.CreateSalesTransaction.TransactionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.createsalestransaction.transactionid(v=AX.60)
ms:contentKeyID: 65321629
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.CreateSalesTransaction.TransactionId
dev_langs:
- CSharp
- C++
- VB
---

# TransactionId Property

Gets or sets transaction id argument.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property TransactionId As InArgument(Of String)
    Get
    Set
'Usage
Dim instance As CreateSalesTransaction
Dim value As InArgument(Of String)

value = instance.TransactionId

instance.TransactionId = value
```

``` csharp
public InArgument<string> TransactionId { get; set; }
```

``` c++
public:
property InArgument<String^>^ TransactionId {
    InArgument<String^>^ get ();
    void set (InArgument<String^>^ value);
}
```

#### Property Value

Type: InArgument\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns InArgument.  

## See Also

#### Reference

[CreateSalesTransaction Class](createsalestransaction-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

