---
title: NonBindableActionController.GetBarcodeById Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetBarcodeById Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetBarcodeById(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getbarcodebyid(v=AX.60)
ms:contentKeyID: 62203367
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetBarcodeById
dev_langs:
- CSharp
- C++
- VB
---

# GetBarcodeById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets barcode by identifier.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Overridable Function GetBarcodeById ( _
    parameters As ODataActionParameters _
) As Barcode
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim returnValue As Barcode

returnValue = instance.GetBarcodeById(parameters)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public virtual Barcode GetBarcodeById(
    ODataActionParameters parameters
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
virtual Barcode^ GetBarcodeById(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: Barcode  
The barcode object.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

