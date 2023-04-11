---
title: TransferOrdersController.Commit Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Commit Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.TransferOrdersController.Commit(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.transferorderscontroller.commit(v=AX.60)
ms:contentKeyID: 62202862
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.TransferOrdersController.Commit
dev_langs:
- CSharp
- C++
- VB
---

# Commit Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Commits a transfer order.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.PickingAndReceiving)> _
<HttpPostAttribute> _
Public Overridable Sub Commit ( _
    key As String _
)
'Usage
Dim instance As TransferOrdersController
Dim key As String

instance.Commit(key)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.PickingAndReceiving)]
[HttpPostAttribute]
public virtual void Commit(
    string key
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::PickingAndReceiving)]
[HttpPostAttribute]
public:
virtual void Commit(
    String^ key
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransferOrdersController Class](transferorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

