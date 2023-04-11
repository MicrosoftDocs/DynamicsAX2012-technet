---
title: Transaction Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Transaction Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transaction(v=AX.60)
ms:contentKeyID: 62213438
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction
dev_langs:
- CSharp
- C++
- VB
---

# Transaction Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents a channel agnostic transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class Transaction _
    Inherits CommerceEntity
'Usage
Dim instance As Transaction
```

``` csharp
[DataContractAttribute]
public abstract class Transaction : CommerceEntity
```

``` c++
[DataContractAttribute]
public ref class Transaction abstract : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionLog](transactionlog-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

