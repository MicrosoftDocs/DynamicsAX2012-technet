---
title: CurrencyL2CacheDataStoreAccessor.PutCurrencyByCode Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutCurrencyByCode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor.PutCurrencyByCode(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.currencyl2cachedatastoreaccessor.putcurrencybycode(v=AX.60)
ms:contentKeyID: 65315666
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor.PutCurrencyByCode
dev_langs:
- CSharp
- C++
- VB
---

# PutCurrencyByCode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Puts the currency by code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutCurrencyByCode ( _
    currencyCode As String, _
    columns As ColumnSet, _
    result As Currency _
)
'Usage
Dim instance As CurrencyL2CacheDataStoreAccessor
Dim currencyCode As String
Dim columns As ColumnSet
Dim result As Currency

instance.PutCurrencyByCode(currencyCode, _
    columns, result)
```

``` csharp
public void PutCurrencyByCode(
    string currencyCode,
    ColumnSet columns,
    Currency result
)
```

``` c++
public:
void PutCurrencyByCode(
    String^ currencyCode, 
    ColumnSet^ columns, 
    Currency^ result
)
```

#### Parameters

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CurrencyL2CacheDataStoreAccessor Class](currencyl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

