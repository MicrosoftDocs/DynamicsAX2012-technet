---
title: BufferResponseContentAttribute.AllowMultiple Property  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: AllowMultiple Property
ms:assetid: P:Microsoft.Dynamics.Retail.RetailServerLibrary.BufferResponseContentAttribute.AllowMultiple
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.bufferresponsecontentattribute.allowmultiple(v=AX.60)
ms:contentKeyID: 62203662
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.BufferResponseContentAttribute.AllowMultiple
dev_langs:
- CSharp
- C++
- VB
---

# AllowMultiple Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether allow multiple buffers.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property AllowMultiple As Boolean
    Get
'Usage
Dim instance As BufferResponseContentAttribute
Dim value As Boolean

value = instance.AllowMultiple
```

``` csharp
public bool AllowMultiple { get; }
```

``` c++
public:
virtual property bool AllowMultiple {
    bool get () sealed;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

#### Implements

IFilterAllowMultiple()  

## See Also

#### Reference

[BufferResponseContentAttribute Class](bufferresponsecontentattribute-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

