---
title: PaymentConnectorConfiguration.ConnectorProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ConnectorProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentConnectorConfiguration.ConnectorProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentconnectorconfiguration.connectorproperties(v=AX.60)
ms:contentKeyID: 65317092
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentConnectorConfiguration.ConnectorProperties
dev_langs:
- CSharp
- C++
- VB
---

# ConnectorProperties Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PROPERTIES")> _
Public Property ConnectorProperties As String
    Get
    Friend Set
'Usage
Dim instance As PaymentConnectorConfiguration
Dim value As String

value = instance.ConnectorProperties
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PROPERTIES")]
public string ConnectorProperties { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PROPERTIES")]
public:
property String^ ConnectorProperties {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[PaymentConnectorConfiguration Class](paymentconnectorconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

