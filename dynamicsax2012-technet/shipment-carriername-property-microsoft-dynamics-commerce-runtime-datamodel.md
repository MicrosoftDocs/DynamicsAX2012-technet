---
title: Shipment.CarrierName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CarrierName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.CarrierName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipment.carriername(v=AX.60)
ms:contentKeyID: 62201813
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.CarrierName
dev_langs:
- CSharp
- C++
- VB
---

# CarrierName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the carrier name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CARRIERNAME")> _
<DataMemberAttribute> _
Public Property CarrierName As String
    Get
    Set
'Usage
Dim instance As Shipment
Dim value As String

value = instance.CarrierName

instance.CarrierName = value
```

``` csharp
[ColumnAttribute("CARRIERNAME")]
[DataMemberAttribute]
public string CarrierName { get; set; }
```

``` c++
[ColumnAttribute(L"CARRIERNAME")]
[DataMemberAttribute]
public:
property String^ CarrierName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The carrier name related to this shipment.  

## See Also

#### Reference

[Shipment Class](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

