---
title: IStoreInventoryServicesV1.CommitOrderReceipt Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CommitOrderReceipt Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServicesV1.CommitOrderReceipt(System.String,System.String,Microsoft.Dynamics.Retail.Pos.Contracts.Services.PRCountingType)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.istoreinventoryservicesv1.commitorderreceipt(v=AX.60)
ms:contentKeyID: 47344354
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServicesV1.CommitOrderReceipt
dev_langs:
- CSharp
- C++
- VB
---

# CommitOrderReceipt Method

Commits an order receipt document by sending it back to HQ.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CommitOrderReceipt ( _
    orderId As String, _
    receiptNumber As String, _
    prType As PRCountingType _
) As IPRDocument
'Usage
Dim instance As IStoreInventoryServicesV1
Dim orderId As String
Dim receiptNumber As String
Dim prType As PRCountingType
Dim returnValue As IPRDocument

returnValue = instance.CommitOrderReceipt(orderId, _
    receiptNumber, prType)
```

``` csharp
IPRDocument CommitOrderReceipt(
    string orderId,
    string receiptNumber,
    PRCountingType prType
)
```

``` c++
IPRDocument^ CommitOrderReceipt(
    String^ orderId, 
    String^ receiptNumber, 
    PRCountingType prType
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - prType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.PRCountingType](prcountingtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPRDocument](iprdocument-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The PRDocument document.  

## See Also

#### Reference

[IStoreInventoryServicesV1 Interface](istoreinventoryservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

