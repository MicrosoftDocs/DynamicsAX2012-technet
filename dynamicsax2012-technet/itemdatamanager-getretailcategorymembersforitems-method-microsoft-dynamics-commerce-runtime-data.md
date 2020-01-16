---
title: ItemDataManager.GetRetailCategoryMembersForItems Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetRetailCategoryMembersForItems Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.GetRetailCategoryMembersForItems(System.Collections.Generic.ISet{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.itemdatamanager.getretailcategorymembersforitems(v=AX.60)
ms:contentKeyID: 62213846
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.GetRetailCategoryMembersForItems
dev_langs:
- CSharp
- C++
- VB
---

# GetRetailCategoryMembersForItems Method

Get the category membership information for the product or variant identifiers passed in.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetRetailCategoryMembersForItems ( _
    productOrVariantIds As ISet(Of Long) _
) As ReadOnlyCollection(Of RetailCategoryMember)
'Usage
Dim instance As ItemDataManager
Dim productOrVariantIds As ISet(Of Long)
Dim returnValue As ReadOnlyCollection(Of RetailCategoryMember)

returnValue = instance.GetRetailCategoryMembersForItems(productOrVariantIds)
```

``` csharp
public ReadOnlyCollection<RetailCategoryMember> GetRetailCategoryMembersForItems(
    ISet<long> productOrVariantIds
)
```

``` c++
public:
virtual ReadOnlyCollection<RetailCategoryMember^>^ GetRetailCategoryMembersForItems(
    ISet<long long>^ productOrVariantIds
) sealed
```

#### Parameters

  - productOrVariantIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[RetailCategoryMember](retailcategorymember-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of mappings between the product or variant identifier and the category identifier.  

#### Implements

[IItemDataManager.GetRetailCategoryMembersForItems(ISet\<Int64\>)](iitemdatamanager-getretailcategorymembersforitems-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ItemDataManager Class](itemdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

