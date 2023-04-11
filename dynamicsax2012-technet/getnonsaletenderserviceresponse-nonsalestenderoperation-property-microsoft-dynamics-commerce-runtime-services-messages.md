---
title: GetNonSaleTenderServiceResponse.NonSalesTenderOperation Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NonSalesTenderOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNonSaleTenderServiceResponse.NonSalesTenderOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getnonsaletenderserviceresponse.nonsalestenderoperation(v=AX.60)
ms:contentKeyID: 62208918
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNonSaleTenderServiceResponse.NonSalesTenderOperation
dev_langs:
- CSharp
- C++
- VB
---

# NonSalesTenderOperation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of non sale tender operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NonSalesTenderOperation As ReadOnlyCollection(Of NonSalesTransaction)
    Get
    Private Set
'Usage
Dim instance As GetNonSaleTenderServiceResponse
Dim value As ReadOnlyCollection(Of NonSalesTransaction)

value = instance.NonSalesTenderOperation
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<NonSalesTransaction> NonSalesTenderOperation { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<NonSalesTransaction^>^ NonSalesTenderOperation {
    ReadOnlyCollection<NonSalesTransaction^>^ get ();
    private: void set (ReadOnlyCollection<NonSalesTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetNonSaleTenderServiceResponse Class](getnonsaletenderserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

