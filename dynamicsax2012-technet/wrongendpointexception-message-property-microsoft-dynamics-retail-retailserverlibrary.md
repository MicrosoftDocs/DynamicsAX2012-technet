---
title: WrongEndpointException.Message Property  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: Message Property
ms:assetid: P:Microsoft.Dynamics.Retail.RetailServerLibrary.WrongEndpointException.Message
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.wrongendpointexception.message(v=AX.60)
ms:contentKeyID: 62203481
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.WrongEndpointException.Message
dev_langs:
- CSharp
- C++
- VB
---

# Message Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the error message.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property Message As String
    Get
'Usage
Dim instance As WrongEndpointException
Dim value As String

value = instance.Message
```

``` csharp
public override string Message { get; }
```

``` c++
public:
virtual property String^ Message {
    String^ get () override;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

#### Implements

[\_Exception.Message](https://technet.microsoft.com/library/b4sz7awd\(v=ax.60\))  

## See Also

#### Reference

[WrongEndpointException Class](wrongendpointexception-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

