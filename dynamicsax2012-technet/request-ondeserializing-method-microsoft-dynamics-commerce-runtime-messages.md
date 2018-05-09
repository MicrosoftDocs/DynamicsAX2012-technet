---
title: Request.OnDeserializing Method  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OnDeserializing Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.Request.OnDeserializing(System.Runtime.Serialization.StreamingContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.request.ondeserializing(v=AX.60)
ms:contentKeyID: 65315467
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.Request.OnDeserializing
dev_langs:
- CSharp
- C++
- VB
---

# OnDeserializing Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<OnDeserializingAttribute> _
Public Sub OnDeserializing ( _
    context As StreamingContext _
)
'Usage
Dim instance As Request
Dim context As StreamingContext

instance.OnDeserializing(context)
```

``` csharp
[OnDeserializingAttribute]
public void OnDeserializing(
    StreamingContext context
)
```

``` c++
[OnDeserializingAttribute]
public:
void OnDeserializing(
    StreamingContext context
)
```

#### Parameters

  - context  
    Type: [System.Runtime.Serialization.StreamingContext](https://technet.microsoft.com/en-us/library/t16abws5\(v=ax.60\))  

## See Also

#### Reference

[Request Class](request-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

