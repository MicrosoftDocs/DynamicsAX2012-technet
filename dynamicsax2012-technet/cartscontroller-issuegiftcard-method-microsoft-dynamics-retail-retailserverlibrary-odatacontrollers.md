---
title: CartsController.IssueGiftCard Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: IssueGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.IssueGiftCard(System.String,System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.cartscontroller.issuegiftcard(v=AX.60)
ms:contentKeyID: 62202638
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.IssueGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# IssueGiftCard Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Issues gift card.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.IssueGiftCertificate)> _
Public Overridable Function IssueGiftCard ( _
    key As String, _
    parameters As ODataActionParameters _
) As Cart
'Usage
Dim instance As CartsController
Dim key As String
Dim parameters As ODataActionParameters
Dim returnValue As Cart

returnValue = instance.IssueGiftCard(key, _
    parameters)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.IssueGiftCertificate)]
public virtual Cart IssueGiftCard(
    string key,
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::IssueGiftCertificate)]
public:
virtual Cart^ IssueGiftCard(
    String^ key, 
    ODataActionParameters^ parameters
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: Cart  
The cart object containing added gift card line.  

## See Also

#### Reference

[CartsController Class](cartscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

