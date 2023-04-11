---
title: DeviceConfiguration.RefundSale Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RefundSale Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.RefundSale
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.refundsale(v=AX.60)
ms:contentKeyID: 62202969
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.RefundSale
dev_langs:
- CSharp
- C++
- VB
---

# RefundSale Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the refund sale reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("REFUNDSALE")> _
Public Property RefundSale As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.RefundSale

instance.RefundSale = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("REFUNDSALE")]
public string RefundSale { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"REFUNDSALE")]
public:
property String^ RefundSale {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the refund sale reason code.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

