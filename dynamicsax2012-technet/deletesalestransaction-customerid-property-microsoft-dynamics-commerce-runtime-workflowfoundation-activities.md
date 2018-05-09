---
title: DeleteSalesTransaction.CustomerId Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: CustomerId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.DeleteSalesTransaction.CustomerId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.deletesalestransaction.customerid(v=AX.60)
ms:contentKeyID: 65318631
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.DeleteSalesTransaction.CustomerId
dev_langs:
- CSharp
- C++
- VB
---

# CustomerId Property

Gets or sets customer id argument.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property CustomerId As InArgument(Of String)
    Get
    Set
'Usage
Dim instance As DeleteSalesTransaction
Dim value As InArgument(Of String)

value = instance.CustomerId

instance.CustomerId = value
```

``` csharp
public InArgument<string> CustomerId { get; set; }
```

``` c++
public:
property InArgument<String^>^ CustomerId {
    InArgument<String^>^ get ();
    void set (InArgument<String^>^ value);
}
```

#### Property Value

Type: InArgument\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
Returns InArgument.  

## See Also

#### Reference

[DeleteSalesTransaction Class](deletesalestransaction-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

