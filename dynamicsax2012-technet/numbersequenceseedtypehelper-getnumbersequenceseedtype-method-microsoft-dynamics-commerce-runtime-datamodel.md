---
title: NumberSequenceSeedTypeHelper.GetNumberSequenceSeedType Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetNumberSequenceSeedType Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedTypeHelper.GetNumberSequenceSeedType(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.numbersequenceseedtypehelper.getnumbersequenceseedtype(v=AX.60)
ms:contentKeyID: 65322147
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedTypeHelper.GetNumberSequenceSeedType
dev_langs:
- CSharp
- C++
- VB
---

# GetNumberSequenceSeedType Method

Get the number sequence type from the receipt transaction type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetNumberSequenceSeedType ( _
    receiptTransactionType As ReceiptTransactionType _
) As NumberSequenceSeedType
'Usage
Dim receiptTransactionType As ReceiptTransactionType
Dim returnValue As NumberSequenceSeedType

returnValue = NumberSequenceSeedTypeHelper.GetNumberSequenceSeedType(receiptTransactionType)
```

``` csharp
public static NumberSequenceSeedType GetNumberSequenceSeedType(
    ReceiptTransactionType receiptTransactionType
)
```

``` c++
public:
static NumberSequenceSeedType GetNumberSequenceSeedType(
    ReceiptTransactionType receiptTransactionType
)
```

#### Parameters

  - receiptTransactionType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType](receipttransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType](numbersequenceseedtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The number sequence type.  

## See Also

#### Reference

[NumberSequenceSeedTypeHelper Class](numbersequenceseedtypehelper-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

