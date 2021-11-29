---
title: GetUnitsOfMeasureRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetUnitsOfMeasureRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetUnitsOfMeasureRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getunitsofmeasurerequesthandler.process(v=AX.60)
ms:contentKeyID: 62207889
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetUnitsOfMeasureRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow associated with retrieving list of units of measure.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetUnitsOfMeasureRequest _
) As GetUnitsOfMeasureResponse
'Usage
Dim request As GetUnitsOfMeasureRequest
Dim returnValue As GetUnitsOfMeasureResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetUnitsOfMeasureResponse Process(
    GetUnitsOfMeasureRequest request
)
```

``` c++
protected:
virtual GetUnitsOfMeasureResponse^ Process(
    GetUnitsOfMeasureRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetUnitsOfMeasureRequest](getunitsofmeasurerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetUnitsOfMeasureResponse](getunitsofmeasureresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[GetUnitsOfMeasureRequestHandler Class](getunitsofmeasurerequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

