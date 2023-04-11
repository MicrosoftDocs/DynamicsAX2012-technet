---
title: UpdateReturnQuantitiesDataRequest.SalesLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SalesLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateReturnQuantitiesDataRequest.SalesLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.updatereturnquantitiesdatarequest.saleslines(v=AX.60)
ms:contentKeyID: 65321690
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateReturnQuantitiesDataRequest.SalesLines
dev_langs:
- CSharp
- C++
- VB
---

# SalesLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales lines to be updated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesLines As IEnumerable(Of SalesLine)
    Get
    Private Set
'Usage
Dim instance As UpdateReturnQuantitiesDataRequest
Dim value As IEnumerable(Of SalesLine)

value = instance.SalesLines
```

``` csharp
[DataMemberAttribute]
public IEnumerable<SalesLine> SalesLines { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<SalesLine^>^ SalesLines {
    IEnumerable<SalesLine^>^ get ();
    private: void set (IEnumerable<SalesLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[UpdateReturnQuantitiesDataRequest Class](updatereturnquantitiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

