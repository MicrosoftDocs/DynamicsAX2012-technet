---
title: DeleteStockCountTransactionDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: DeleteStockCountTransactionDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteStockCountTransactionDataRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.deletestockcounttransactiondatarequest.deletestockcounttransactiondatarequest(v=AX.60)
ms:contentKeyID: 65321315
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteStockCountTransactionDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DeleteStockCountTransactionDataRequest Constructor

Initializes a new instance of the [DeleteStockCountTransactionDataRequest](deletestockcounttransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

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

Dim instance As New DeleteStockCountTransactionDataRequest(journalId, _
    itemId, inventSizeId, inventColorId, _
    inventStyleId, configId)
```

``` csharp
public DeleteStockCountTransactionDataRequest(
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
DeleteStockCountTransactionDataRequest(
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
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventSizeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventColorId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventStyleId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - configId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DeleteStockCountTransactionDataRequest Class](deletestockcounttransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

