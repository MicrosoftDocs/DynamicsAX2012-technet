---
title: ControllerAssemblyResolver.GetAssemblies Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetAssemblies Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ControllerAssemblyResolver.GetAssemblies
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.controllerassemblyresolver.getassemblies(v=AX.60)
ms:contentKeyID: 62202319
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ControllerAssemblyResolver.GetAssemblies
dev_langs:
- CSharp
- C++
- VB
---

# GetAssemblies Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets assemblies.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function GetAssemblies As ICollection(Of Assembly)
'Usage
Dim instance As ControllerAssemblyResolver
Dim returnValue As ICollection(Of Assembly)

returnValue = instance.GetAssemblies()
```

``` csharp
public override ICollection<Assembly> GetAssemblies()
```

``` c++
public:
virtual ICollection<Assembly^>^ GetAssemblies() override
```

#### Return Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Assembly](https://technet.microsoft.com/library/xbe1wdx9\(v=ax.60\))\>  
The list of assemblies.  

#### Implements

IAssembliesResolverGetAssemblies()  

## See Also

#### Reference

[ControllerAssemblyResolver Class](controllerassemblyresolver-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

