---
title: ICompanyRequestHandler.SupportedCompanies Property  (Microsoft.Dynamics.Commerce.Runtime.Handlers)
TOCTitle: SupportedCompanies Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Handlers.ICompanyRequestHandler.SupportedCompanies
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.handlers.icompanyrequesthandler.supportedcompanies(v=AX.60)
ms:contentKeyID: 65322725
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Handlers.ICompanyRequestHandler.SupportedCompanies
dev_langs:
- CSharp
- C++
- VB
---

# SupportedCompanies Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a collection of companies supported by this request handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Handlers](microsoft-dynamics-commerce-runtime-handlers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property SupportedCompanies As IEnumerable(Of String)
    Get
'Usage
Dim instance As ICompanyRequestHandler
Dim value As IEnumerable(Of String)

value = instance.SupportedCompanies
```

``` csharp
IEnumerable<string> SupportedCompanies { get; }
```

``` c++
property IEnumerable<String^>^ SupportedCompanies {
    IEnumerable<String^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ICompanyRequestHandler Interface](icompanyrequesthandler-interface-microsoft-dynamics-commerce-runtime-handlers.md)

[Microsoft.Dynamics.Commerce.Runtime.Handlers Namespace](microsoft-dynamics-commerce-runtime-handlers-namespace.md)

