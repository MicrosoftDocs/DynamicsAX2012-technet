---
title: GetShipmentLineMappingDataRequest.SalesOrderIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SalesOrderIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShipmentLineMappingDataRequest.SalesOrderIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getshipmentlinemappingdatarequest.salesorderids(v=AX.60)
ms:contentKeyID: 65321666
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShipmentLineMappingDataRequest.SalesOrderIds
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrderIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales order identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesOrderIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As GetShipmentLineMappingDataRequest
Dim value As IEnumerable(Of String)

value = instance.SalesOrderIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> SalesOrderIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ SalesOrderIds {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
The sales order identifiers.  

## See Also

#### Reference

[GetShipmentLineMappingDataRequest Class](getshipmentlinemappingdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

