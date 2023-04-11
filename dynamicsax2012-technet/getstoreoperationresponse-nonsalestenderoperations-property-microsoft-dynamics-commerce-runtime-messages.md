---
title: GetStoreOperationResponse.NonSalesTenderOperations Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: NonSalesTenderOperations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreOperationResponse.NonSalesTenderOperations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoreoperationresponse.nonsalestenderoperations(v=AX.60)
ms:contentKeyID: 62215065
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreOperationResponse.NonSalesTenderOperations
dev_langs:
- CSharp
- C++
- VB
---

# NonSalesTenderOperations Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the non sale tender operations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NonSalesTenderOperations As ReadOnlyCollection(Of NonSalesTransaction)
    Get
    Private Set
'Usage
Dim instance As GetStoreOperationResponse
Dim value As ReadOnlyCollection(Of NonSalesTransaction)

value = instance.NonSalesTenderOperations
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<NonSalesTransaction> NonSalesTenderOperations { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<NonSalesTransaction^>^ NonSalesTenderOperations {
    ReadOnlyCollection<NonSalesTransaction^>^ get ();
    private: void set (ReadOnlyCollection<NonSalesTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetStoreOperationResponse Class](getstoreoperationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

