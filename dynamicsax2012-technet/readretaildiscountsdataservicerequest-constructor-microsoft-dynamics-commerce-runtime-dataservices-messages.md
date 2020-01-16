---
title: ReadRetailDiscountsDataServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ReadRetailDiscountsDataServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReadRetailDiscountsDataServiceRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit},System.Collections.Generic.ISet{System.String},System.DateTimeOffset,System.DateTimeOffset,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.readretaildiscountsdataservicerequest.readretaildiscountsdataservicerequest(v=AX.60)
ms:contentKeyID: 65321092
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReadRetailDiscountsDataServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ReadRetailDiscountsDataServiceRequest Constructor

Initializes a new instance of the [ReadRetailDiscountsDataServiceRequest](readretaildiscountsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    items As IEnumerable(Of ItemUnit), _
    priceGroups As ISet(Of String), _
    minActiveDate As DateTimeOffset, _
    maxActiveDate As DateTimeOffset, _
    currencyCode As String _
)
'Usage
Dim items As IEnumerable(Of ItemUnit)
Dim priceGroups As ISet(Of String)
Dim minActiveDate As DateTimeOffset
Dim maxActiveDate As DateTimeOffset
Dim currencyCode As String

Dim instance As New ReadRetailDiscountsDataServiceRequest(items, priceGroups, _
    minActiveDate, maxActiveDate, currencyCode)
```

``` csharp
public ReadRetailDiscountsDataServiceRequest(
    IEnumerable<ItemUnit> items,
    ISet<string> priceGroups,
    DateTimeOffset minActiveDate,
    DateTimeOffset maxActiveDate,
    string currencyCode
)
```

``` c++
public:
ReadRetailDiscountsDataServiceRequest(
    IEnumerable<ItemUnit^>^ items, 
    ISet<String^>^ priceGroups, 
    DateTimeOffset minActiveDate, 
    DateTimeOffset maxActiveDate, 
    String^ currencyCode
)
```

#### Parameters

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemUnit](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - priceGroups  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - minActiveDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - maxActiveDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ReadRetailDiscountsDataServiceRequest Class](readretaildiscountsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

