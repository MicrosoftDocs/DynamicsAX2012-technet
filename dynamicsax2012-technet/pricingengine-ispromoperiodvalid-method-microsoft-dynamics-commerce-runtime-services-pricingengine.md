---
title: PricingEngine.IsPromoPeriodValid Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: IsPromoPeriodValid Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PricingEngine.IsPromoPeriodValid(Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager,Microsoft.Dynamics.Commerce.Runtime.DataModel.DateValidationType,System.String,System.DateTimeOffset,System.DateTimeOffset,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricingengine.ispromoperiodvalid(v=AX.60)
ms:contentKeyID: 62211089
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PricingEngine.IsPromoPeriodValid
dev_langs:
- CSharp
- C++
- VB
---

# IsPromoPeriodValid Method

Computes the validity of a promotion period. If it's an advanced period, looks up the validation period by Id and tests it.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function IsPromoPeriodValid ( _
    pricingDataManager As IPricingDataManager, _
    validationType As DateValidationType, _
    validationPeriodId As String, _
    startDate As DateTimeOffset, _
    endDate As DateTimeOffset, _
    dateToCheck As DateTimeOffset _
) As Boolean
'Usage
Dim pricingDataManager As IPricingDataManager
Dim validationType As DateValidationType
Dim validationPeriodId As String
Dim startDate As DateTimeOffset
Dim endDate As DateTimeOffset
Dim dateToCheck As DateTimeOffset
Dim returnValue As Boolean

returnValue = PricingEngine.IsPromoPeriodValid(pricingDataManager, _
    validationType, validationPeriodId, _
    startDate, endDate, dateToCheck)
```

``` csharp
public static bool IsPromoPeriodValid(
    IPricingDataManager pricingDataManager,
    DateValidationType validationType,
    string validationPeriodId,
    DateTimeOffset startDate,
    DateTimeOffset endDate,
    DateTimeOffset dateToCheck
)
```

``` c++
public:
static bool IsPromoPeriodValid(
    IPricingDataManager^ pricingDataManager, 
    DateValidationType validationType, 
    String^ validationPeriodId, 
    DateTimeOffset startDate, 
    DateTimeOffset endDate, 
    DateTimeOffset dateToCheck
)
```

#### Parameters

  - pricingDataManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager](ipricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - validationType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DateValidationType](datevalidationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - validationPeriodId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - startDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - endDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - dateToCheck  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if given period info is active on date being checked.  

## See Also

#### Reference

[PricingEngine Class](pricingengine-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

