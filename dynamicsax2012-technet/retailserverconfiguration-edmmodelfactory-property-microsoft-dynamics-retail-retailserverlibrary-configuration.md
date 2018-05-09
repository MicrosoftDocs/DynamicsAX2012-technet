---
title: RetailServerConfiguration.EdmModelFactory Property  (Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration)
TOCTitle: EdmModelFactory Property
ms:assetid: P:Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration.RetailServerConfiguration.EdmModelFactory
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.configuration.retailserverconfiguration.edmmodelfactory(v=AX.60)
ms:contentKeyID: 62202132
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration.RetailServerConfiguration.EdmModelFactory
dev_langs:
- CSharp
- C++
- VB
---

# EdmModelFactory Property

Gets the EDM model factory object.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration](microsoft-dynamics-retail-retailserverlibrary-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly Property EdmModelFactory As IEdmModelFactory
    Get
'Usage
Dim value As IEdmModelFactory

value = RetailServerConfiguration.EdmModelFactory
```

``` csharp
public static IEdmModelFactory EdmModelFactory { get; }
```

``` c++
public:
static property IEdmModelFactory^ EdmModelFactory {
    IEdmModelFactory^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.RetailServerLibrary.IEdmModelFactory](iedmmodelfactory-interface-microsoft-dynamics-retail-retailserverlibrary.md)  
Returns [IEdmModelFactory](iedmmodelfactory-interface-microsoft-dynamics-retail-retailserverlibrary.md).  

## See Also

#### Reference

[RetailServerConfiguration Class](retailserverconfiguration-class-microsoft-dynamics-retail-retailserverlibrary-configuration.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration Namespace](microsoft-dynamics-retail-retailserverlibrary-configuration-namespace.md)

