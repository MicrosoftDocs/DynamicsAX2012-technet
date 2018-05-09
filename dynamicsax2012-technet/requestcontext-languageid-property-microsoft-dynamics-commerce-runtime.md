---
title: RequestContext.LanguageId Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: LanguageId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.RequestContext.LanguageId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.requestcontext.languageid(v=AX.60)
ms:contentKeyID: 62210622
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContext.LanguageId
dev_langs:
- CSharp
- C++
- VB
---

# LanguageId Property

Gets the language identifier for the current request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property LanguageId As String
    Get
    Set
'Usage
Dim instance As RequestContext
Dim value As String

value = instance.LanguageId

instance.LanguageId = value
```

``` csharp
public string LanguageId { get; set; }
```

``` c++
public:
property String^ LanguageId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[RequestContext Class](requestcontext-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

