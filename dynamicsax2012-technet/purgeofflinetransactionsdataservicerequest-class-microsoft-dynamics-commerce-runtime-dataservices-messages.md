---
title: PurgeOfflineTransactionsDataServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: PurgeOfflineTransactionsDataServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeOfflineTransactionsDataServiceRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.purgeofflinetransactionsdataservicerequest(v=AX.60)
ms:contentKeyID: 65317405
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeOfflineTransactionsDataServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# PurgeOfflineTransactionsDataServiceRequest Class

The data service request to purge transactions from offline transaction DB based on transaction IDs provided.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class PurgeOfflineTransactionsDataServiceRequest _
    Inherits DataRequest
'Usage
Dim instance As PurgeOfflineTransactionsDataServiceRequest
```

``` csharp
[DataContractAttribute]
public class PurgeOfflineTransactionsDataServiceRequest : DataRequest
```

``` c++
[DataContractAttribute]
public ref class PurgeOfflineTransactionsDataServiceRequest : public DataRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DataRequest](datarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeOfflineTransactionsDataServiceRequest  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

