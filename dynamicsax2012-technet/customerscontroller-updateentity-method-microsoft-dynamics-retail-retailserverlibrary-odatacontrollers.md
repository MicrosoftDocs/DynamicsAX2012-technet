---
title: CustomersController.UpdateEntity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: UpdateEntity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CustomersController.UpdateEntity(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.customerscontroller.updateentity(v=AX.60)
ms:contentKeyID: 62202839
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CustomersController.UpdateEntity
dev_langs:
- CSharp
- C++
- VB
---

# UpdateEntity Method

Updates Customer entity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.CustomerEdit)> _
Protected Overrides Function UpdateEntity ( _
    key As String, _
    update As Customer _
) As Customer
'Usage
Dim key As String
Dim update As Customer
Dim returnValue As Customer

returnValue = Me.UpdateEntity(key, _
    update)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.CustomerEdit)]
protected override Customer UpdateEntity(
    string key,
    Customer update
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::CustomerEdit)]
protected:
virtual Customer^ UpdateEntity(
    String^ key, 
    Customer^ update
) override
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - update  
    Type: Customer  

#### Return Value

Type: Customer  
The Customer.  

## See Also

#### Reference

[CustomersController Class](customerscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

