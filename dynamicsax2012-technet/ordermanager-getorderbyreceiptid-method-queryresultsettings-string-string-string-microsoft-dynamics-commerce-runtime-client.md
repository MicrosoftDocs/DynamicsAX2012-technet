---
title: OrderManager.GetOrderByReceiptId Method (QueryResultSettings, String, String, String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOrderByReceiptId Method (QueryResultSettings, String, String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetOrderByReceiptId(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getorderbyreceiptid(v=AX.60)
ms:contentKeyID: 65322388
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetOrderByReceiptId Method (QueryResultSettings, String, String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOrderByReceiptId ( _
    settings As QueryResultSettings, _
    receiptId As String, _
    orderStoreNumber As String, _
    orderTerminalId As String _
) As IEnumerable(Of SalesOrder)
'Usage
Dim instance As OrderManager
Dim settings As QueryResultSettings
Dim receiptId As String
Dim orderStoreNumber As String
Dim orderTerminalId As String
Dim returnValue As IEnumerable(Of SalesOrder)

returnValue = instance.GetOrderByReceiptId(settings, _
    receiptId, orderStoreNumber, orderTerminalId)
```

``` csharp
public IEnumerable<SalesOrder> GetOrderByReceiptId(
    QueryResultSettings settings,
    string receiptId,
    string orderStoreNumber,
    string orderTerminalId
)
```

``` c++
public:
IEnumerable<SalesOrder^>^ GetOrderByReceiptId(
    QueryResultSettings^ settings, 
    String^ receiptId, 
    String^ orderStoreNumber, 
    String^ orderTerminalId
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - receiptId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - orderStoreNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - orderTerminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetOrderByReceiptId Overload](ordermanager-getorderbyreceiptid-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

