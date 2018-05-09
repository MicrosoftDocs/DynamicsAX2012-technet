---
title: Request.ExtractSerializedParameters Method  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ExtractSerializedParameters Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.Request.ExtractSerializedParameters
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.request.extractserializedparameters(v=AX.60)
ms:contentKeyID: 49843753
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.Request.ExtractSerializedParameters
dev_langs:
- CSharp
- C++
- VB
---

# ExtractSerializedParameters Method

Serializes the parameters. Used for logging purposes. The user should override this method with a custom implementation if the default xml serialization of the object would be too big for the database row.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function ExtractSerializedParameters As String
'Usage
Dim returnValue As String

returnValue = Me.ExtractSerializedParameters()
```

``` csharp
protected virtual string ExtractSerializedParameters()
```

``` c++
protected:
virtual String^ ExtractSerializedParameters()
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Serialized parameters.  

## See Also

#### Reference

[Request Class](request-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

