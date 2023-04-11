---
title: SaveStoreOperationResponse.NonSalesTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: NonSalesTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStoreOperationResponse.NonSalesTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savestoreoperationresponse.nonsalestransaction(v=AX.60)
ms:contentKeyID: 62203456
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStoreOperationResponse.NonSalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# NonSalesTransaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the non sale tender operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NonSalesTransaction As NonSalesTransaction
    Get
    Private Set
'Usage
Dim instance As SaveStoreOperationResponse
Dim value As NonSalesTransaction

value = instance.NonSalesTransaction
```

``` csharp
[DataMemberAttribute]
public NonSalesTransaction NonSalesTransaction { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property NonSalesTransaction^ NonSalesTransaction {
    NonSalesTransaction^ get ();
    private: void set (NonSalesTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveStoreOperationResponse Class](savestoreoperationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

