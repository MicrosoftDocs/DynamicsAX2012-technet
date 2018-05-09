---
title: ICompositionLoader.RequestPipeline Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: RequestPipeline Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader.RequestPipeline
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.icompositionloader.requestpipeline(v=AX.60)
ms:contentKeyID: 65319954
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader.RequestPipeline
dev_langs:
- CSharp
- C++
- VB
---

# RequestPipeline Property

Gets the handler to execute the pipeline.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property RequestPipeline As IRequestPipeline
    Get
'Usage
Dim instance As ICompositionLoader
Dim value As IRequestPipeline

value = instance.RequestPipeline
```

``` csharp
IRequestPipeline RequestPipeline { get; }
```

``` c++
property IRequestPipeline^ RequestPipeline {
    IRequestPipeline^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Workflow.IRequestPipeline](irequestpipeline-interface-microsoft-dynamics-commerce-runtime-workflow.md)  
Returns [IRequestPipeline](irequestpipeline-interface-microsoft-dynamics-commerce-runtime-workflow.md).  

## See Also

#### Reference

[ICompositionLoader Interface](icompositionloader-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

