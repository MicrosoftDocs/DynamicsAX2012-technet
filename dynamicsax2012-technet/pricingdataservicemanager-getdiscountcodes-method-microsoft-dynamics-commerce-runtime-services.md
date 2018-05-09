---
title: PricingDataServiceManager.GetDiscountCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetDiscountCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetDiscountCodes(System.String,System.String,System.String,System.DateTime,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getdiscountcodes(v=AX.60)
ms:contentKeyID: 65315469
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetDiscountCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountCodes Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetDiscountCodes ( _
    offerId As String, _
    discountCode As String, _
    keyword As String, _
    activeDate As DateTime, _
    resultSettings As QueryResultSettings _
) As ReadOnlyCollection(Of DiscountCode)
'Usage
Dim instance As PricingDataServiceManager
Dim offerId As String
Dim discountCode As String
Dim keyword As String
Dim activeDate As DateTime
Dim resultSettings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of DiscountCode)

returnValue = instance.GetDiscountCodes(offerId, _
    discountCode, keyword, activeDate, _
    resultSettings)
```

``` csharp
public ReadOnlyCollection<DiscountCode> GetDiscountCodes(
    string offerId,
    string discountCode,
    string keyword,
    DateTime activeDate,
    QueryResultSettings resultSettings
)
```

``` c++
public:
ReadOnlyCollection<DiscountCode^>^ GetDiscountCodes(
    String^ offerId, 
    String^ discountCode, 
    String^ keyword, 
    DateTime activeDate, 
    QueryResultSettings^ resultSettings
)
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - discountCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - keyword  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activeDate  
    Type: [System.DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - resultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

