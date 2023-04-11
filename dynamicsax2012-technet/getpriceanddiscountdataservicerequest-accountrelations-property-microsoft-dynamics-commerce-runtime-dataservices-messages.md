---
title: GetPriceAndDiscountDataServiceRequest.AccountRelations Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: AccountRelations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.AccountRelations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest.accountrelations(v=AX.60)
ms:contentKeyID: 65322069
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.AccountRelations
dev_langs:
- CSharp
- C++
- VB
---

# AccountRelations Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the account relations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AccountRelations As IEnumerable(Of String)
    Get
    Protected Set
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
Dim value As IEnumerable(Of String)

value = instance.AccountRelations

instance.AccountRelations = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> AccountRelations { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ AccountRelations {
    IEnumerable<String^>^ get ();
    protected: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetPriceAndDiscountDataServiceRequest Class](getpriceanddiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

