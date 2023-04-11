---
title: LineDeliveryPreference.LineId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDeliveryPreference.LineId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.linedeliverypreference.lineid(v=AX.60)
ms:contentKeyID: 65320166
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDeliveryPreference.LineId
dev_langs:
- CSharp
- C++
- VB
---

# LineId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales line identifier for which the delivery preferences are computed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineId As String
    Get
    Private Set
'Usage
Dim instance As LineDeliveryPreference
Dim value As String

value = instance.LineId
```

``` csharp
[DataMemberAttribute]
public string LineId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LineId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The sales line identifier.  

## See Also

#### Reference

[LineDeliveryPreference Class](linedeliverypreference-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

