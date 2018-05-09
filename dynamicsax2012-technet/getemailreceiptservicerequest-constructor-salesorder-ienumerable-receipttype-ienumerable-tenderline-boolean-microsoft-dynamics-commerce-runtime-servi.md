---
title: GetEmailReceiptServiceRequest Constructor (SalesOrder, IEnumerable(ReceiptType), IEnumerable(TenderLine), Boolean) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetEmailReceiptServiceRequest Constructor (SalesOrder, IEnumerable(ReceiptType), IEnumerable(TenderLine), Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType},System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getemailreceiptservicerequest.getemailreceiptservicerequest(v=AX.60)
ms:contentKeyID: 65316219
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetEmailReceiptServiceRequest Constructor (SalesOrder, IEnumerable(ReceiptType), IEnumerable(TenderLine), Boolean)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesOrder As SalesOrder, _
    receiptTypes As IEnumerable(Of ReceiptType), _
    tenderLines As IEnumerable(Of TenderLine), _
    isCopy As Boolean _
)
'Usage
Dim salesOrder As SalesOrder
Dim receiptTypes As IEnumerable(Of ReceiptType)
Dim tenderLines As IEnumerable(Of TenderLine)
Dim isCopy As Boolean

Dim instance As New GetEmailReceiptServiceRequest(salesOrder, _
    receiptTypes, tenderLines, isCopy)
```

``` csharp
public GetEmailReceiptServiceRequest(
    SalesOrder salesOrder,
    IEnumerable<ReceiptType> receiptTypes,
    IEnumerable<TenderLine> tenderLines,
    bool isCopy
)
```

``` c++
public:
GetEmailReceiptServiceRequest(
    SalesOrder^ salesOrder, 
    IEnumerable<ReceiptType>^ receiptTypes, 
    IEnumerable<TenderLine^>^ tenderLines, 
    bool isCopy
)
```

#### Parameters

  - salesOrder  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - receiptTypes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - tenderLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - isCopy  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetEmailReceiptServiceRequest Class](getemailreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetEmailReceiptServiceRequest Overload](getemailreceiptservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

