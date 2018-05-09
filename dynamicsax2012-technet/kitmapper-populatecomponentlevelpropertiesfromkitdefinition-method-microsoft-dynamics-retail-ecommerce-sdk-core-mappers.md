---
title: KitMapper.PopulateComponentLevelPropertiesFromKitDefinition Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers)
TOCTitle: PopulateComponentLevelPropertiesFromKitDefinition Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers.KitMapper.PopulateComponentLevelPropertiesFromKitDefinition(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem,Microsoft.Dynamics.Commerce.Runtime.DataModel.Product,System.Collections.Generic.Dictionary{System.Int64,System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.mappers.kitmapper.populatecomponentlevelpropertiesfromkitdefinition(v=AX.60)
ms:contentKeyID: 65317641
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers.KitMapper.PopulateComponentLevelPropertiesFromKitDefinition
dev_langs:
- CSharp
- C++
- VB
---

# PopulateComponentLevelPropertiesFromKitDefinition Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers](microsoft-dynamics-retail-ecommerce-sdk-core-mappers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Sub PopulateComponentLevelPropertiesFromKitDefinition ( _
    transactionItem As TransactionItem, _
    kitProductMaster As Product, _
    variantToMasterLookup As Dictionary(Of Long, Long) _
)
'Usage
Dim transactionItem As TransactionItem
Dim kitProductMaster As Product
Dim variantToMasterLookup As Dictionary(Of Long, Long)

Me.PopulateComponentLevelPropertiesFromKitDefinition(transactionItem, _
    kitProductMaster, variantToMasterLookup)
```

``` csharp
protected virtual void PopulateComponentLevelPropertiesFromKitDefinition(
    TransactionItem transactionItem,
    Product kitProductMaster,
    Dictionary<long, long> variantToMasterLookup
)
```

``` c++
protected:
virtual void PopulateComponentLevelPropertiesFromKitDefinition(
    TransactionItem^ transactionItem, 
    Product^ kitProductMaster, 
    Dictionary<long long, long long>^ variantToMasterLookup
)
```

#### Parameters

  - transactionItem  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem](transactionitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

<!-- end list -->

  - kitProductMaster  
    Type: Product  

<!-- end list -->

  - variantToMasterLookup  
    Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/en-us/library/xfhwa508\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)), [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[KitMapper Class](kitmapper-class-microsoft-dynamics-retail-ecommerce-sdk-core-mappers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-mappers-namespace.md)

