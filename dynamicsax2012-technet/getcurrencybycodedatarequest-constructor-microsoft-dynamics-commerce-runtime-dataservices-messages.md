---
title: GetCurrencyByCodeDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetCurrencyByCodeDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCurrencyByCodeDataRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcurrencybycodedatarequest.getcurrencybycodedatarequest(v=AX.60)
ms:contentKeyID: 65321681
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCurrencyByCodeDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrencyByCodeDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetCurrencyByCodeDataRequest](getcurrencybycodedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    currencyCode As String, _
    columns As ColumnSet _
)
'Usage
Dim currencyCode As String
Dim columns As ColumnSet

Dim instance As New GetCurrencyByCodeDataRequest(currencyCode, _
    columns)
```

``` csharp
public GetCurrencyByCodeDataRequest(
    string currencyCode,
    ColumnSet columns
)
```

``` c++
public:
GetCurrencyByCodeDataRequest(
    String^ currencyCode, 
    ColumnSet^ columns
)
```

#### Parameters

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[GetCurrencyByCodeDataRequest Class](getcurrencybycodedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

