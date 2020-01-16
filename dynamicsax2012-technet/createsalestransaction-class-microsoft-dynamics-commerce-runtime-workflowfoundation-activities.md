---
title: CreateSalesTransaction Class (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: CreateSalesTransaction Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.CreateSalesTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.createsalestransaction(v=AX.60)
ms:contentKeyID: 65317044
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.CreateSalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# CreateSalesTransaction Class

Activity that creates sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class CreateSalesTransaction _
    Inherits CodeActivity(Of SalesTransaction)
'Usage
Dim instance As CreateSalesTransaction
```

``` csharp
public sealed class CreateSalesTransaction : CodeActivity<SalesTransaction>
```

``` c++
public ref class CreateSalesTransaction sealed : public CodeActivity<SalesTransaction^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Activity  
    ActivityWithResult  
      Activity\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
        CodeActivity\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
          Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.CreateSalesTransaction  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

