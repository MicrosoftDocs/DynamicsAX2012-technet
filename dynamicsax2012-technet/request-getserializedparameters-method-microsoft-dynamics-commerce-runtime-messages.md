---
title: Request.GetSerializedParameters Method  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetSerializedParameters Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.Request.GetSerializedParameters
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.request.getserializedparameters(v=AX.60)
ms:contentKeyID: 49832760
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.Request.GetSerializedParameters
dev_langs:
- CSharp
- C++
- VB
---

# GetSerializedParameters Method

Serializes the parameters. Used for logging purposes. This call must never fail.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function GetSerializedParameters As String
'Usage
Dim instance As Request
Dim returnValue As String

returnValue = instance.GetSerializedParameters()
```

``` csharp
public string GetSerializedParameters()
```

``` c++
public:
String^ GetSerializedParameters()
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Serialized parameters.  

## See Also

#### Reference

[Request Class](request-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

