---
title: PickingListsController.PatchEntity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: PatchEntity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PickingListsController.PatchEntity(System.String,System.Web.Http.OData.Delta{Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.pickinglistscontroller.patchentity(v=AX.60)
ms:contentKeyID: 62201749
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PickingListsController.PatchEntity
dev_langs:
- CSharp
- C++
- VB
---

# PatchEntity Method

Saves a picking list in the local database.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.PickingAndReceiving)> _
<HttpPatchAttribute> _
Protected Overrides Function PatchEntity ( _
    key As String, _
    patch As Delta(Of PickingList) _
) As PickingList
'Usage
Dim key As String
Dim patch As Delta(Of PickingList)
Dim returnValue As PickingList

returnValue = Me.PatchEntity(key, _
    patch)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.PickingAndReceiving)]
[HttpPatchAttribute]
protected override PickingList PatchEntity(
    string key,
    Delta<PickingList> patch
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::PickingAndReceiving)]
[HttpPatchAttribute]
protected:
virtual PickingList^ PatchEntity(
    String^ key, 
    Delta<PickingList^>^ patch
) override
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - patch  
    Type: Delta\<PickingList\>  

#### Return Value

Type: PickingList  
The saved picking list.  

## See Also

#### Reference

[PickingListsController Class](pickinglistscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

