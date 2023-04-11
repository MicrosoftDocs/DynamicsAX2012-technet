---
title: GetOfflineTransactionCountResponse.OfflineTransactionCount Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OfflineTransactionCount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineTransactionCountResponse.OfflineTransactionCount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getofflinetransactioncountresponse.offlinetransactioncount(v=AX.60)
ms:contentKeyID: 65315743
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineTransactionCountResponse.OfflineTransactionCount
dev_langs:
- CSharp
- C++
- VB
---

# OfflineTransactionCount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OfflineTransactionCount As Integer
    Get
    Private Set
'Usage
Dim instance As GetOfflineTransactionCountResponse
Dim value As Integer

value = instance.OfflineTransactionCount
```

``` csharp
[DataMemberAttribute]
public int OfflineTransactionCount { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property int OfflineTransactionCount {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[GetOfflineTransactionCountResponse Class](getofflinetransactioncountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

