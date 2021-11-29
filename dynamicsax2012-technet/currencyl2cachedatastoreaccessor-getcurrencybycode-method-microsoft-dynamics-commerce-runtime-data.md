---
title: CurrencyL2CacheDataStoreAccessor.GetCurrencyByCode Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCurrencyByCode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor.GetCurrencyByCode(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.currencyl2cachedatastoreaccessor.getcurrencybycode(v=AX.60)
ms:contentKeyID: 65317905
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor.GetCurrencyByCode
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrencyByCode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the currency by code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCurrencyByCode ( _
    currencyCode As String, _
    columns As ColumnSet _
) As Currency
'Usage
Dim instance As CurrencyL2CacheDataStoreAccessor
Dim currencyCode As String
Dim columns As ColumnSet
Dim returnValue As Currency

returnValue = instance.GetCurrencyByCode(currencyCode, _
    columns)
```

``` csharp
public Currency GetCurrencyByCode(
    string currencyCode,
    ColumnSet columns
)
```

``` c++
public:
virtual Currency^ GetCurrencyByCode(
    String^ currencyCode, 
    ColumnSet^ columns
) sealed
```

#### Parameters

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The currency or NULL if not found.  

#### Implements

[ICurrencyDataManager.GetCurrencyByCode(String, ColumnSet)](icurrencydatamanager-getcurrencybycode-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[CurrencyL2CacheDataStoreAccessor Class](currencyl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

