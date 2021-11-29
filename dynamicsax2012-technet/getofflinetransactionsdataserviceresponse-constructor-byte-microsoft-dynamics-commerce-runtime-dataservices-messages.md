---
title: GetOfflineTransactionsDataServiceResponse Constructor (Byte ) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetOfflineTransactionsDataServiceResponse Constructor (Byte )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineTransactionsDataServiceResponse.#ctor(System.Byte[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getofflinetransactionsdataserviceresponse.getofflinetransactionsdataserviceresponse(v=AX.60)
ms:contentKeyID: 65316718
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetOfflineTransactionsDataServiceResponse Constructor (Byte[])


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetOfflineTransactionsDataServiceResponse](getofflinetransactionsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    compressedTransactions As Byte() _
)
'Usage
Dim compressedTransactions As Byte()

Dim instance As New GetOfflineTransactionsDataServiceResponse(compressedTransactions)
```

``` csharp
public GetOfflineTransactionsDataServiceResponse(
    byte[] compressedTransactions
)
```

``` c++
public:
GetOfflineTransactionsDataServiceResponse(
    array<unsigned char>^ compressedTransactions
)
```

#### Parameters

  - compressedTransactions  
    Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  

## See Also

#### Reference

[GetOfflineTransactionsDataServiceResponse Class](getofflinetransactionsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetOfflineTransactionsDataServiceResponse Overload](getofflinetransactionsdataserviceresponse-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

