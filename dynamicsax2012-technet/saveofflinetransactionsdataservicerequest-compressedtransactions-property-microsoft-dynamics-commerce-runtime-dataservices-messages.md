---
title: SaveOfflineTransactionsDataServiceRequest.CompressedTransactions Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CompressedTransactions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveOfflineTransactionsDataServiceRequest.CompressedTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.saveofflinetransactionsdataservicerequest.compressedtransactions(v=AX.60)
ms:contentKeyID: 65316590
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveOfflineTransactionsDataServiceRequest.CompressedTransactions
dev_langs:
- CSharp
- C++
- VB
---

# CompressedTransactions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the compressed offline transactions. We use industry standard Gnu Zip algorithm.

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
Dim instance As SaveOfflineTransactionsDataServiceRequest
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

[SaveOfflineTransactionsDataServiceRequest Class](saveofflinetransactionsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

