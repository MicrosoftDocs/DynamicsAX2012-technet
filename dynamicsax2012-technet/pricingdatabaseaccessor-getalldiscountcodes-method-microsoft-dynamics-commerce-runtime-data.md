---
title: PricingDatabaseAccessor.GetAllDiscountCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAllDiscountCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetAllDiscountCodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatabaseaccessor.getalldiscountcodes(v=AX.60)
ms:contentKeyID: 62214933
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetAllDiscountCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetAllDiscountCodes Method

Get the discount codes available in the system configuration, including the mapping to discount offers for each discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetAllDiscountCodes As ReadOnlyCollection(Of DiscountCode)
'Usage
Dim instance As PricingDatabaseAccessor
Dim returnValue As ReadOnlyCollection(Of DiscountCode)

returnValue = instance.GetAllDiscountCodes()
```

``` csharp
public ReadOnlyCollection<DiscountCode> GetAllDiscountCodes()
```

``` c++
public:
ReadOnlyCollection<DiscountCode^>^ GetAllDiscountCodes()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of discount codes.  

## See Also

#### Reference

[PricingDatabaseAccessor Class](pricingdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

