---
title: IPurchaseOrderV1.ReceivePurchaseOrder Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ReceivePurchaseOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPurchaseOrderV1.ReceivePurchaseOrder(System.String,System.String,Microsoft.Dynamics.Retail.Pos.Contracts.Services.PRCountingType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ipurchaseorderv1.receivepurchaseorder(v=AX.60)
ms:contentKeyID: 47344100
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPurchaseOrderV1.ReceivePurchaseOrder
dev_langs:
- CSharp
- C++
- VB
---

# ReceivePurchaseOrder Method

Invokes receiving UI for a given PurchaseOrderReceipt value.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ReceivePurchaseOrder ( _
    poNumber As String, _
    receiptNumber As String, _
    prType As PRCountingType _
)
'Usage
Dim instance As IPurchaseOrderV1
Dim poNumber As String
Dim receiptNumber As String
Dim prType As PRCountingType

instance.ReceivePurchaseOrder(poNumber, _
    receiptNumber, prType)
```

``` csharp
void ReceivePurchaseOrder(
    string poNumber,
    string receiptNumber,
    PRCountingType prType
)
```

``` c++
void ReceivePurchaseOrder(
    String^ poNumber, 
    String^ receiptNumber, 
    PRCountingType prType
)
```

#### Parameters

  - poNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - prType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.PRCountingType](prcountingtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

## See Also

#### Reference

[IPurchaseOrderV1 Interface](ipurchaseorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

