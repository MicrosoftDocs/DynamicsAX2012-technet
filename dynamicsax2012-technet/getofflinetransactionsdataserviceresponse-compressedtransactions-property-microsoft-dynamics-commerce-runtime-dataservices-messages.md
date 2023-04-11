---
title: GetOfflineTransactionsDataServiceResponse.CompressedTransactions Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CompressedTransactions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineTransactionsDataServiceResponse.CompressedTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getofflinetransactionsdataserviceresponse.compressedtransactions(v=AX.60)
ms:contentKeyID: 65320220
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineTransactionsDataServiceResponse.CompressedTransactions
dev_langs:
- CSharp
- C++
- VB
---

# CompressedTransactions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Gnu Zip compressed byte sequence for the requested offline transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CompressedTransactions As Byte()
    Get
    Private Set
'Usage
Dim instance As GetOfflineTransactionsDataServiceResponse
Dim value As Byte()

value = instance.CompressedTransactions
```

``` csharp
[DataMemberAttribute]
public byte[] CompressedTransactions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property array<unsigned char>^ CompressedTransactions {
    array<unsigned char>^ get ();
    private: void set (array<unsigned char>^ value);
}
```

#### Property Value

Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  
Returns [Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\)).  

## See Also

#### Reference

[GetOfflineTransactionsDataServiceResponse Class](getofflinetransactionsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

