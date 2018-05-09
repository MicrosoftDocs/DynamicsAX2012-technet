---
title: PaymentConnectorConfiguration.IsTestMode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsTestMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentConnectorConfiguration.IsTestMode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.paymentconnectorconfiguration.istestmode(v=AX.60)
ms:contentKeyID: 49849096
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentConnectorConfiguration.IsTestMode
dev_langs:
- CSharp
- C++
- VB
---

# IsTestMode Property

Gets a value indicating whether the connector is in test mode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISTESTMODE")> _
Public Property IsTestMode As Boolean
    Get
    Friend Set
'Usage
Dim instance As PaymentConnectorConfiguration
Dim value As Boolean

value = instance.IsTestMode
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISTESTMODE")]
public bool IsTestMode { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISTESTMODE")]
public:
property bool IsTestMode {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[PaymentConnectorConfiguration Class](paymentconnectorconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

