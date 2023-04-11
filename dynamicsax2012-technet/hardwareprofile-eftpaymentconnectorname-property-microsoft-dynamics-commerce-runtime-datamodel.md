---
title: HardwareProfile.EftPaymentConnectorName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EftPaymentConnectorName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EFTPaymentConnectorName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.eftpaymentconnectorname(v=AX.60)
ms:contentKeyID: 62210806
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EftPaymentConnectorName
dev_langs:
- CSharp
- C++
- VB
---

# EftPaymentConnectorName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EFTCONNECTORNAME")> _
<DataMemberAttribute> _
Public Property EftPaymentConnectorName As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.EftPaymentConnectorName

instance.EftPaymentConnectorName = value
```

``` csharp
[ColumnAttribute("EFTCONNECTORNAME")]
[DataMemberAttribute]
public string EftPaymentConnectorName { get; set; }
```

``` c++
[ColumnAttribute(L"EFTCONNECTORNAME")]
[DataMemberAttribute]
public:
property String^ EftPaymentConnectorName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

