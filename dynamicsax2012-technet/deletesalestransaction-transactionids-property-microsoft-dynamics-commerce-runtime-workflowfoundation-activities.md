---
title: DeleteSalesTransaction.TransactionIds Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: TransactionIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.DeleteSalesTransaction.TransactionIds
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.deletesalestransaction.transactionids(v=AX.60)
ms:contentKeyID: 65316345
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.DeleteSalesTransaction.TransactionIds
dev_langs:
- CSharp
- C++
- VB
---

# TransactionIds Property

Gets or sets transaction id argument.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property TransactionIds As InArgument(Of IEnumerable(Of String))
    Get
    Set
'Usage
Dim instance As DeleteSalesTransaction
Dim value As InArgument(Of IEnumerable(Of String))

value = instance.TransactionIds

instance.TransactionIds = value
```

``` csharp
public InArgument<IEnumerable<string>> TransactionIds { get; set; }
```

``` c++
public:
property InArgument<IEnumerable<String^>^>^ TransactionIds {
    InArgument<IEnumerable<String^>^>^ get ();
    void set (InArgument<IEnumerable<String^>^>^ value);
}
```

#### Property Value

Type: InArgument\<[IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>\>  
Returns InArgument.  

## See Also

#### Reference

[DeleteSalesTransaction Class](deletesalestransaction-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

