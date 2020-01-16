---
title: IPricingDataManager.GetVariantByItemIdAndInventDimId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetVariantByItemIdAndInventDimId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetVariantByItemIdAndInventDimId(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanager.getvariantbyitemidandinventdimid(v=AX.60)
ms:contentKeyID: 49844906
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetVariantByItemIdAndInventDimId
dev_langs:
- CSharp
- C++
- VB
---

# GetVariantByItemIdAndInventDimId Method

Gets the variant info for given item identifier and variant inventory dimension identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetVariantByItemIdAndInventDimId ( _
    itemId As String, _
    inventDimId As String, _
    columnSet As ColumnSet _
) As ProductVariant
'Usage
Dim instance As IPricingDataManager
Dim itemId As String
Dim inventDimId As String
Dim columnSet As ColumnSet
Dim returnValue As ProductVariant

returnValue = instance.GetVariantByItemIdAndInventDimId(itemId, _
    inventDimId, columnSet)
```

``` csharp
ProductVariant GetVariantByItemIdAndInventDimId(
    string itemId,
    string inventDimId,
    ColumnSet columnSet
)
```

``` c++
ProductVariant^ GetVariantByItemIdAndInventDimId(
    String^ itemId, 
    String^ inventDimId, 
    ColumnSet^ columnSet
)
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
The variant with specified columns populated. Null if variant not found.  

## See Also

#### Reference

[IPricingDataManager Interface](ipricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

