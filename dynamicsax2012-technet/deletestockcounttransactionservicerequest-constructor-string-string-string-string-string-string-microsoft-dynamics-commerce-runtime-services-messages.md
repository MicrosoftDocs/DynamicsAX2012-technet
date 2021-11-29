---
title: DeleteStockCountTransactionServiceRequest Constructor (String, String, String, String, String, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DeleteStockCountTransactionServiceRequest Constructor (String, String, String, String, String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteStockCountTransactionServiceRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.deletestockcounttransactionservicerequest.deletestockcounttransactionservicerequest(v=AX.60)
ms:contentKeyID: 65319571
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DeleteStockCountTransactionServiceRequest Constructor (String, String, String, String, String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    journalId As String, _
    itemId As String, _
    inventSizeId As String, _
    inventColorId As String, _
    inventStyleId As String, _
    configId As String _
)
'Usage
Dim journalId As String
Dim itemId As String
Dim inventSizeId As String
Dim inventColorId As String
Dim inventStyleId As String
Dim configId As String

Dim instance As New DeleteStockCountTransactionServiceRequest(journalId, _
    itemId, inventSizeId, inventColorId, _
    inventStyleId, configId)
```

``` csharp
public DeleteStockCountTransactionServiceRequest(
    string journalId,
    string itemId,
    string inventSizeId,
    string inventColorId,
    string inventStyleId,
    string configId
)
```

``` c++
public:
DeleteStockCountTransactionServiceRequest(
    String^ journalId, 
    String^ itemId, 
    String^ inventSizeId, 
    String^ inventColorId, 
    String^ inventStyleId, 
    String^ configId
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventSizeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventColorId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventStyleId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - configId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DeleteStockCountTransactionServiceRequest Class](deletestockcounttransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[DeleteStockCountTransactionServiceRequest Overload](deletestockcounttransactionservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

