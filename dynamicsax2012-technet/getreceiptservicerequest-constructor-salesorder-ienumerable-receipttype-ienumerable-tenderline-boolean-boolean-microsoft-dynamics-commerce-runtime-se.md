---
title: GetReceiptServiceRequest Constructor (SalesOrder, IEnumerable(ReceiptType), IEnumerable(TenderLine), Boolean, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetReceiptServiceRequest Constructor (SalesOrder, IEnumerable(ReceiptType), IEnumerable(TenderLine), Boolean, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType},System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine},System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreceiptservicerequest.getreceiptservicerequest(v=AX.60)
ms:contentKeyID: 65316580
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReceiptServiceRequest Constructor (SalesOrder, IEnumerable(ReceiptType), IEnumerable(TenderLine), Boolean, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesOrder As SalesOrder, _
    receiptTypes As IEnumerable(Of ReceiptType), _
    tenderLines As IEnumerable(Of TenderLine), _
    isCopy As Boolean, _
    isPreview As Boolean _
)
'Usage
Dim salesOrder As SalesOrder
Dim receiptTypes As IEnumerable(Of ReceiptType)
Dim tenderLines As IEnumerable(Of TenderLine)
Dim isCopy As Boolean
Dim isPreview As Boolean

Dim instance As New GetReceiptServiceRequest(salesOrder, _
    receiptTypes, tenderLines, isCopy, _
    isPreview)
```

``` csharp
public GetReceiptServiceRequest(
    SalesOrder salesOrder,
    IEnumerable<ReceiptType> receiptTypes,
    IEnumerable<TenderLine> tenderLines,
    bool isCopy,
    bool isPreview
)
```

``` c++
public:
GetReceiptServiceRequest(
    SalesOrder^ salesOrder, 
    IEnumerable<ReceiptType>^ receiptTypes, 
    IEnumerable<TenderLine^>^ tenderLines, 
    bool isCopy, 
    bool isPreview
)
```

#### Parameters

  - salesOrder  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - receiptTypes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - tenderLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - isCopy  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - isPreview  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetReceiptServiceRequest Class](getreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetReceiptServiceRequest Overload](getreceiptservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

