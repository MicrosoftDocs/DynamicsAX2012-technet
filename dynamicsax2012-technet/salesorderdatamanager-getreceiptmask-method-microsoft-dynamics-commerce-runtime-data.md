---
title: SalesOrderDataManager.GetReceiptMask Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReceiptMask Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetReceiptMask(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.getreceiptmask(v=AX.60)
ms:contentKeyID: 62210454
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetReceiptMask
dev_langs:
- CSharp
- C++
- VB
---

# GetReceiptMask Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the receipt mask by functionality profile Id and receipt transaction type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetReceiptMask ( _
    functionalityProfileId As String, _
    receiptTransactionType As ReceiptTransactionType _
) As ReceiptMask
'Usage
Dim instance As SalesOrderDataManager
Dim functionalityProfileId As String
Dim receiptTransactionType As ReceiptTransactionType
Dim returnValue As ReceiptMask

returnValue = instance.GetReceiptMask(functionalityProfileId, _
    receiptTransactionType)
```

``` csharp
public ReceiptMask GetReceiptMask(
    string functionalityProfileId,
    ReceiptTransactionType receiptTransactionType
)
```

``` c++
public:
ReceiptMask^ GetReceiptMask(
    String^ functionalityProfileId, 
    ReceiptTransactionType receiptTransactionType
)
```

#### Parameters

  - functionalityProfileId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptTransactionType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType](receipttransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptMask](receiptmask-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The receipt mask.  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

