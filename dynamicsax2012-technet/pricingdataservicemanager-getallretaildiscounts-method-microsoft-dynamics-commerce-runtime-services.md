---
title: PricingDataServiceManager.GetAllRetailDiscounts Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetAllRetailDiscounts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetAllRetailDiscounts
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getallretaildiscounts(v=AX.60)
ms:contentKeyID: 65319077
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetAllRetailDiscounts
dev_langs:
- CSharp
- C++
- VB
---

# GetAllRetailDiscounts Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetAllRetailDiscounts As ReadOnlyCollection(Of RetailDiscount)
'Usage
Dim instance As PricingDataServiceManager
Dim returnValue As ReadOnlyCollection(Of RetailDiscount)

returnValue = instance.GetAllRetailDiscounts()
```

``` csharp
public ReadOnlyCollection<RetailDiscount> GetAllRetailDiscounts()
```

``` c++
public:
virtual ReadOnlyCollection<RetailDiscount^>^ GetAllRetailDiscounts() sealed
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[RetailDiscount](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IPricingDataManagerV2.GetAllRetailDiscounts()](ipricingdatamanagerv2-getallretaildiscounts-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

