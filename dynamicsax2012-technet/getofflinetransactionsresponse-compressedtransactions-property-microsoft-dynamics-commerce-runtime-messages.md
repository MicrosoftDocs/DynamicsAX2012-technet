---
title: GetOfflineTransactionsResponse.CompressedTransactions Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CompressedTransactions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineTransactionsResponse.CompressedTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getofflinetransactionsresponse.compressedtransactions(v=AX.60)
ms:contentKeyID: 65319315
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineTransactionsResponse.CompressedTransactions
dev_langs:
- CSharp
- C++
- VB
---

# CompressedTransactions Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CompressedTransactions As Byte()
    Get
    Private Set
'Usage
Dim instance As GetOfflineTransactionsResponse
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

## See Also

#### Reference

[GetOfflineTransactionsResponse Class](getofflinetransactionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

