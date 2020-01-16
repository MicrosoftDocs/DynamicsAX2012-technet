---
title: PricingDataManager.GetDiscountCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDiscountCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetDiscountCodes(System.String,System.String,System.String,System.DateTime,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatamanager.getdiscountcodes(v=AX.60)
ms:contentKeyID: 65315601
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetDiscountCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountCodes Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

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
Dim instance As PricingDataManager
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
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - discountCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - keyword  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activeDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - resultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[PricingDataManager Class](pricingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

