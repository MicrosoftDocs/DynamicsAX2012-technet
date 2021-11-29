---
title: Request.Parameters Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Parameters Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.Request.Parameters
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.request.parameters(v=AX.60)
ms:contentKeyID: 49840991
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.Request.Parameters
dev_langs:
- CSharp
- C++
- VB
---

# Parameters Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the parameters in the reqeust.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property Parameters As ParameterSet
    Get
    Private Set
'Usage
Dim instance As Request
Dim value As ParameterSet

value = instance.Parameters
```

``` csharp
[IgnoreDataMemberAttribute]
public ParameterSet Parameters { get; private set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ParameterSet^ Parameters {
    ParameterSet^ get ();
    private: void set (ParameterSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  
Returns [ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[Request Class](request-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

