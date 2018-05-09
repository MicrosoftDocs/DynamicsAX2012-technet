---
title: TransactionLog Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionLog Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionLog
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.transactionlog(v=AX.60)
ms:contentKeyID: 62211895
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionLog
dev_langs:
- CSharp
- C++
- VB
---

# TransactionLog Class

Represents a channel agnostic transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class TransactionLog _
    Inherits Transaction
'Usage
Dim instance As TransactionLog
```

``` csharp
[DataContractAttribute]
public class TransactionLog : Transaction
```

``` c++
[DataContractAttribute]
public ref class TransactionLog : public Transaction
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction](transaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionLog  
        [Microsoft.Dynamics.Commerce.Runtime.DataModel.KitTransaction](kittransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

