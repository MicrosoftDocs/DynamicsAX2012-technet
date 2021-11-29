---
title: CommerceController(TEntity, TKey) Class (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: CommerceController(TEntity, TKey) Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceController`2
ms:mtpsurl: https://technet.microsoft.com/library/Dn737927(v=AX.60)
ms:contentKeyID: 62203134
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceController`2
dev_langs:
- CSharp
- C++
- VB
---

# CommerceController(TEntity, TKey) Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The commerce controller. Abstract class, used as base class for most of controllers.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ModelValidatorAttribute> _
<ComVisibleAttribute(False)> _
Public MustInherit Class CommerceController(Of TEntity As Class, TKey) _
    Inherits EntitySetController(Of TEntity, TKey)
'Usage
Dim instance As CommerceController(Of TEntity, TKey)
```

``` csharp
[ModelValidatorAttribute]
[ComVisibleAttribute(false)]
public abstract class CommerceController<TEntity, TKey> : EntitySetController<TEntity, TKey>
where TEntity : class
```

``` c++
[ModelValidatorAttribute]
[ComVisibleAttribute(false)]
generic<typename TEntity, typename TKey>
where TEntity : ref class
public ref class CommerceController abstract : public EntitySetController<TEntity, TKey>
```

#### Type Parameters

  - TEntity

<!-- end list -->

  - TKey

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  ApiController  
    ODataController  
      EntitySetController\<TEntity, TKey\>  
        Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceController\<TEntity, TKey\>  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController](cartscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CatalogsController](catalogscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CategoriesController](categoriescontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceListsController](commercelistscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CustomersController](customerscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.EmployeesController](employeescontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController](orgunitscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PickingListsController](pickinglistscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ProductsController](productscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PurchaseOrdersController](purchaseorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController](salesorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController](stockcountjournalscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  
          [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.TransferOrdersController](transferorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

