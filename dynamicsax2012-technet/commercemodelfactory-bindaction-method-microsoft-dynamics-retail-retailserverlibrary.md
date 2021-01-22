---
title: CommerceModelFactory.BindAction Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: BindAction Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.BindAction(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.commercemodelfactory.bindaction(v=AX.60)
ms:contentKeyID: 62201997
author: Khairunj
ms.author: daxcpft
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.BindAction
dev_langs:
- CSharp
- C++
- VB
---

# BindAction Method

Binds action in the model builder.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function BindAction ( _
    actionName As String _
) As ActionConfiguration
'Usage
Dim actionName As String
Dim returnValue As ActionConfiguration

returnValue = CommerceModelFactory.BindAction(actionName)
```

``` csharp
protected static ActionConfiguration BindAction(
    string actionName
)
```

``` c++
protected:
static ActionConfiguration^ BindAction(
    String^ actionName
)
```

#### Parameters

  - actionName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: ActionConfiguration  
The ActionConfiguration of the OData.  

## See Also

#### Reference

[CommerceModelFactory Class](commercemodelfactory-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

