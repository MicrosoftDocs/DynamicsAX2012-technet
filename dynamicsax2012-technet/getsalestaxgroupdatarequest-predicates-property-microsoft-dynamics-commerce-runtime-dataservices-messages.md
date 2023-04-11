---
title: GetSalesTaxGroupDataRequest.Predicates Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Predicates Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesTaxGroupDataRequest.Predicates
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getsalestaxgroupdatarequest.predicates(v=AX.60)
ms:contentKeyID: 65322924
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesTaxGroupDataRequest.Predicates
dev_langs:
- CSharp
- C++
- VB
---

# Predicates Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the predicates.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Predicates As Dictionary(Of String, String)
    Get
    Private Set
'Usage
Dim instance As GetSalesTaxGroupDataRequest
Dim value As Dictionary(Of String, String)

value = instance.Predicates
```

``` csharp
[DataMemberAttribute]
public Dictionary<string, string> Predicates { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Dictionary<String^, String^>^ Predicates {
    Dictionary<String^, String^>^ get ();
    private: void set (Dictionary<String^, String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [Dictionary\<TKey, TValue\>](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\)).  

## See Also

#### Reference

[GetSalesTaxGroupDataRequest Class](getsalestaxgroupdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

