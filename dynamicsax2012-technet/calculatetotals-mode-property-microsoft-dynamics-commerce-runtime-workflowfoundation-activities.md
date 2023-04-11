---
title: CalculateTotals.Mode Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: Mode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.CalculateTotals.Mode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.calculatetotals.mode(v=AX.60)
ms:contentKeyID: 65320270
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.CalculateTotals.Mode
dev_langs:
- CSharp
- C++
- VB
---

# Mode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
<RequiredArgumentAttribute> _
Public Property Mode As InArgument(Of CalculationModes)
    Get
    Set
'Usage
Dim instance As CalculateTotals
Dim value As InArgument(Of CalculationModes)

value = instance.Mode

instance.Mode = value
```

``` csharp
[RequiredArgumentAttribute]
public InArgument<CalculationModes> Mode { get; set; }
```

``` c++
[RequiredArgumentAttribute]
public:
property InArgument<CalculationModes>^ Mode {
    InArgument<CalculationModes>^ get ();
    void set (InArgument<CalculationModes>^ value);
}
```

#### Property Value

Type: InArgument\<[CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns InArgument.  

## See Also

#### Reference

[CalculateTotals Class](calculatetotals-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

