---
title: HardwareProfile.EftMerchantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EftMerchantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EFTMerchantId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.eftmerchantid(v=AX.60)
ms:contentKeyID: 62211851
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EftMerchantId
dev_langs:
- CSharp
- C++
- VB
---

# EftMerchantId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EFTMERCHANTID")> _
<DataMemberAttribute> _
Public Property EftMerchantId As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.EftMerchantId

instance.EftMerchantId = value
```

``` csharp
[ColumnAttribute("EFTMERCHANTID")]
[DataMemberAttribute]
public string EftMerchantId { get; set; }
```

``` c++
[ColumnAttribute(L"EFTMERCHANTID")]
[DataMemberAttribute]
public:
property String^ EftMerchantId {
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

