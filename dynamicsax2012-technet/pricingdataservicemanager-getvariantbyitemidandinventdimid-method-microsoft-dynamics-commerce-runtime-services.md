---
title: PricingDataServiceManager.GetVariantByItemIdAndInventDimId Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetVariantByItemIdAndInventDimId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetVariantByItemIdAndInventDimId(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getvariantbyitemidandinventdimid(v=AX.60)
ms:contentKeyID: 65317672
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetVariantByItemIdAndInventDimId
dev_langs:
- CSharp
- C++
- VB
---

# GetVariantByItemIdAndInventDimId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetVariantByItemIdAndInventDimId ( _
    itemId As String, _
    inventDimId As String, _
    columnSet As ColumnSet _
) As ProductVariant
'Usage
Dim instance As PricingDataServiceManager
Dim itemId As String
Dim inventDimId As String
Dim columnSet As ColumnSet
Dim returnValue As ProductVariant

returnValue = instance.GetVariantByItemIdAndInventDimId(itemId, _
    inventDimId, columnSet)
```

``` csharp
public ProductVariant GetVariantByItemIdAndInventDimId(
    string itemId,
    string inventDimId,
    ColumnSet columnSet
)
```

``` c++
public:
virtual ProductVariant^ GetVariantByItemIdAndInventDimId(
    String^ itemId, 
    String^ inventDimId, 
    ColumnSet^ columnSet
) sealed
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventDimId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Implements

[IPricingDataManager.GetVariantByItemIdAndInventDimId(String, String, ColumnSet)](ipricingdatamanager-getvariantbyitemidandinventdimid-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

