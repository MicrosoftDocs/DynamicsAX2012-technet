---
title: NonBindableActionController.GetDeliveryOptions Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetDeliveryOptions Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetDeliveryOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getdeliveryoptions(v=AX.60)
ms:contentKeyID: 62203374
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryOptions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get all delivery options.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Overridable Function GetDeliveryOptions As IEnumerable(Of DeliveryOption)
'Usage
Dim instance As NonBindableActionController
Dim returnValue As IEnumerable(Of DeliveryOption)

returnValue = instance.GetDeliveryOptions()
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public virtual IEnumerable<DeliveryOption> GetDeliveryOptions()
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public:
virtual IEnumerable<DeliveryOption^>^ GetDeliveryOptions()
```

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<DeliveryOption\>  
A collection of delivery options.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

