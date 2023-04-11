---
title: GetTaxCodeIntervalsDataRequest.SalesTaxGroupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SalesTaxGroupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeIntervalsDataRequest.SalesTaxGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.gettaxcodeintervalsdatarequest.salestaxgroupid(v=AX.60)
ms:contentKeyID: 65321109
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeIntervalsDataRequest.SalesTaxGroupId
dev_langs:
- CSharp
- C++
- VB
---

# SalesTaxGroupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales tax group identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesTaxGroupId As String
    Get
    Private Set
'Usage
Dim instance As GetTaxCodeIntervalsDataRequest
Dim value As String

value = instance.SalesTaxGroupId
```

``` csharp
[DataMemberAttribute]
public string SalesTaxGroupId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ SalesTaxGroupId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetTaxCodeIntervalsDataRequest Class](gettaxcodeintervalsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

