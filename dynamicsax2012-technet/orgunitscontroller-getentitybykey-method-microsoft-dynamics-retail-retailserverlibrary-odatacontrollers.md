---
title: OrgUnitsController.GetEntityByKey Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetEntityByKey Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.GetEntityByKey(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.orgunitscontroller.getentitybykey(v=AX.60)
ms:contentKeyID: 62203348
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.GetEntityByKey
dev_langs:
- CSharp
- C++
- VB
---

# GetEntityByKey Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets organization entity by key.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetEntityByKey ( _
    key As String _
) As OrgUnit
'Usage
Dim key As String
Dim returnValue As OrgUnit

returnValue = Me.GetEntityByKey(key)
```

``` csharp
protected override OrgUnit GetEntityByKey(
    string key
)
```

``` c++
protected:
virtual OrgUnit^ GetEntityByKey(
    String^ key
) override
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: OrgUnit  
The OrgUnit.  

## See Also

#### Reference

[OrgUnitsController Class](orgunitscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

