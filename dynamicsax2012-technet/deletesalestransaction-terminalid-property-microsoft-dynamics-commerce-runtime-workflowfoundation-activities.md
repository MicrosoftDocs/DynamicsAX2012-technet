---
title: DeleteSalesTransaction.TerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: TerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.DeleteSalesTransaction.TerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.deletesalestransaction.terminalid(v=AX.60)
ms:contentKeyID: 65320457
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.DeleteSalesTransaction.TerminalId
dev_langs:
- CSharp
- C++
- VB
---

# TerminalId Property

Gets or sets terminal id argument.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property TerminalId As InArgument(Of String)
    Get
    Set
'Usage
Dim instance As DeleteSalesTransaction
Dim value As InArgument(Of String)

value = instance.TerminalId

instance.TerminalId = value
```

``` csharp
public InArgument<string> TerminalId { get; set; }
```

``` c++
public:
property InArgument<String^>^ TerminalId {
    InArgument<String^>^ get ();
    void set (InArgument<String^>^ value);
}
```

#### Property Value

Type: InArgument\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns InArgument.  

## See Also

#### Reference

[DeleteSalesTransaction Class](deletesalestransaction-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

