---
title: ICachedPricingDataManager.PutDiscountCodesByOfferId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutDiscountCodesByOfferId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutDiscountCodesByOfferId(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.ColumnSet,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putdiscountcodesbyofferid(v=AX.60)
ms:contentKeyID: 62212030
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutDiscountCodesByOfferId
dev_langs:
- CSharp
- C++
- VB
---

# PutDiscountCodesByOfferId Method

Get the discount codes (aka 'promo codes') associated with the given discount offer identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutDiscountCodesByOfferId ( _
    offerIds As IEnumerable(Of String), _
    columns As ColumnSet, _
    result As ReadOnlyCollection(Of DiscountCode) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim offerIds As IEnumerable(Of String)
Dim columns As ColumnSet
Dim result As ReadOnlyCollection(Of DiscountCode)

instance.PutDiscountCodesByOfferId(offerIds, _
    columns, result)
```

``` csharp
void PutDiscountCodesByOfferId(
    IEnumerable<string> offerIds,
    ColumnSet columns,
    ReadOnlyCollection<DiscountCode> result
)
```

``` c++
void PutDiscountCodesByOfferId(
    IEnumerable<String^>^ offerIds, 
    ColumnSet^ columns, 
    ReadOnlyCollection<DiscountCode^>^ result
)
```

#### Parameters

  - offerIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

