---
title: TransferOrdersController.GetEntityByKey Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetEntityByKey Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.TransferOrdersController.GetEntityByKey(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.transferorderscontroller.getentitybykey(v=AX.60)
ms:contentKeyID: 62202791
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.TransferOrdersController.GetEntityByKey
dev_langs:
- CSharp
- C++
- VB
---

# GetEntityByKey Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a transfer order by order identifier.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.PickingAndReceiving)> _
Protected Overrides Function GetEntityByKey ( _
    key As String _
) As TransferOrder
'Usage
Dim key As String
Dim returnValue As TransferOrder

returnValue = Me.GetEntityByKey(key)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.PickingAndReceiving)]
protected override TransferOrder GetEntityByKey(
    string key
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::PickingAndReceiving)]
protected:
virtual TransferOrder^ GetEntityByKey(
    String^ key
) override
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: TransferOrder  
A transfer order.  

## See Also

#### Reference

[TransferOrdersController Class](transferorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

