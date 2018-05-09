---
title: KitMapper.PopulateKitItemDetails Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers)
TOCTitle: PopulateKitItemDetails Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers.KitMapper.PopulateKitItemDetails(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem},System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Product},Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.mappers.kitmapper.populatekititemdetails(v=AX.60)
ms:contentKeyID: 65317871
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers.KitMapper.PopulateKitItemDetails
dev_langs:
- CSharp
- C++
- VB
---

# PopulateKitItemDetails Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers](microsoft-dynamics-retail-ecommerce-sdk-core-mappers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Sub PopulateKitItemDetails ( _
    transactionItems As IEnumerable(Of TransactionItem), _
    productDetails As IEnumerable(Of Product), _
    searchEngine As ISearchEngine _
)
'Usage
Dim instance As KitMapper
Dim transactionItems As IEnumerable(Of TransactionItem)
Dim productDetails As IEnumerable(Of Product)
Dim searchEngine As ISearchEngine

instance.PopulateKitItemDetails(transactionItems, _
    productDetails, searchEngine)
```

``` csharp
public virtual void PopulateKitItemDetails(
    IEnumerable<TransactionItem> transactionItems,
    IEnumerable<Product> productDetails,
    ISearchEngine searchEngine
)
```

``` c++
public:
virtual void PopulateKitItemDetails(
    IEnumerable<TransactionItem^>^ transactionItems, 
    IEnumerable<Product^>^ productDetails, 
    ISearchEngine^ searchEngine
)
```

#### Parameters

  - transactionItems  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[TransactionItem](transactionitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

<!-- end list -->

  - productDetails  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<Product\>  

<!-- end list -->

  - searchEngine  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

## See Also

#### Reference

[KitMapper Class](kitmapper-class-microsoft-dynamics-retail-ecommerce-sdk-core-mappers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-mappers-namespace.md)

