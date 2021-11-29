---
title: SaveStoreOperationRequest.NonSalesTenderOperation Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: NonSalesTenderOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStoreOperationRequest.NonSalesTenderOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savestoreoperationrequest.nonsalestenderoperation(v=AX.60)
ms:contentKeyID: 62214788
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStoreOperationRequest.NonSalesTenderOperation
dev_langs:
- CSharp
- C++
- VB
---

# NonSalesTenderOperation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the non sale tender operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NonSalesTenderOperation As NonSalesTransaction
    Get
    Set
'Usage
Dim instance As SaveStoreOperationRequest
Dim value As NonSalesTransaction

value = instance.NonSalesTenderOperation

instance.NonSalesTenderOperation = value
```

``` csharp
[DataMemberAttribute]
public NonSalesTransaction NonSalesTenderOperation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property NonSalesTransaction^ NonSalesTenderOperation {
    NonSalesTransaction^ get ();
    void set (NonSalesTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveStoreOperationRequest Class](savestoreoperationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

