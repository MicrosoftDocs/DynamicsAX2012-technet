---
title: PricingDatabaseAccessor.GetAllRetailDiscountLines Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAllRetailDiscountLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetAllRetailDiscountLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.pricingdatabaseaccessor.getallretaildiscountlines(v=AX.60)
ms:contentKeyID: 62210997
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetAllRetailDiscountLines
dev_langs:
- CSharp
- C++
- VB
---

# GetAllRetailDiscountLines Method

Get the line-specific details for all discounts configured in the system.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetAllRetailDiscountLines As ReadOnlyCollection(Of RetailDiscountLine)
'Usage
Dim instance As PricingDatabaseAccessor
Dim returnValue As ReadOnlyCollection(Of RetailDiscountLine)

returnValue = instance.GetAllRetailDiscountLines()
```

``` csharp
public ReadOnlyCollection<RetailDiscountLine> GetAllRetailDiscountLines()
```

``` c++
public:
ReadOnlyCollection<RetailDiscountLine^>^ GetAllRetailDiscountLines()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[RetailDiscountLine](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of the line details.  

## See Also

#### Reference

[PricingDatabaseAccessor Class](pricingdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

