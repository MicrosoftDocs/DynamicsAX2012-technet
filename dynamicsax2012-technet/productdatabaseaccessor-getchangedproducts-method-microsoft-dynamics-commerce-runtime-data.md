---
title: ProductDatabaseAccessor.GetChangedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChangedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.GetChangedProducts(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityChangeTrackingInformation},Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.productdatabaseaccessor.getchangedproducts(v=AX.60)
ms:contentKeyID: 65321848
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.GetChangedProducts
dev_langs:
- CSharp
- C++
- VB
---

# GetChangedProducts Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChangedProducts ( _
    changedProductsIds As ReadOnlyCollection(Of CommerceEntityChangeTrackingInformation), _
    queryCriteria As ChangedProductsSearchCriteria, _
    settings As QueryResultSettings _
) As ChangedProductsSearchResult
'Usage
Dim instance As ProductDatabaseAccessor
Dim changedProductsIds As ReadOnlyCollection(Of CommerceEntityChangeTrackingInformation)
Dim queryCriteria As ChangedProductsSearchCriteria
Dim settings As QueryResultSettings
Dim returnValue As ChangedProductsSearchResult

returnValue = instance.GetChangedProducts(changedProductsIds, _
    queryCriteria, settings)
```

``` csharp
public ChangedProductsSearchResult GetChangedProducts(
    ReadOnlyCollection<CommerceEntityChangeTrackingInformation> changedProductsIds,
    ChangedProductsSearchCriteria queryCriteria,
    QueryResultSettings settings
)
```

``` c++
public:
ChangedProductsSearchResult^ GetChangedProducts(
    ReadOnlyCollection<CommerceEntityChangeTrackingInformation^>^ changedProductsIds, 
    ChangedProductsSearchCriteria^ queryCriteria, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - changedProductsIds  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[CommerceEntityChangeTrackingInformation](commerceentitychangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - queryCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria](changedproductssearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchResult](changedproductssearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductDatabaseAccessor Class](productdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

