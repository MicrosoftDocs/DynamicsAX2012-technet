---
title: ICCTVV1.CCTVOutput Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CCTVOutput Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICCTVV1.CCTVOutput(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations,System.Boolean,System.Object,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icctvv1.cctvoutput(v=AX.60)
ms:contentKeyID: 47344005
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICCTVV1.CCTVOutput
dev_langs:
- CSharp
- C++
- VB
---

# CCTVOutput Method

Sends an output to a CCTV system.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CCTVOutput ( _
    posTransaction As IPosTransaction, _
    operationId As PosisOperations, _
    mainOperation As Boolean, _
    operationInfo As Object, _
    text As String _
)
'Usage
Dim instance As ICCTVV1
Dim posTransaction As IPosTransaction
Dim operationId As PosisOperations
Dim mainOperation As Boolean
Dim operationInfo As Object
Dim text As String

instance.CCTVOutput(posTransaction, operationId, _
    mainOperation, operationInfo, text)
```

``` csharp
void CCTVOutput(
    IPosTransaction posTransaction,
    PosisOperations operationId,
    bool mainOperation,
    Object operationInfo,
    string text
)
```

``` c++
void CCTVOutput(
    IPosTransaction^ posTransaction, 
    PosisOperations operationId, 
    bool mainOperation, 
    Object^ operationInfo, 
    String^ text
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - operationId  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations](posisoperations-enumeration-microsoft-dynamics-retail-pos-contracts.md)  

<!-- end list -->

  - mainOperation  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - operationInfo  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - text  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ICCTVV1 Interface](icctvv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

