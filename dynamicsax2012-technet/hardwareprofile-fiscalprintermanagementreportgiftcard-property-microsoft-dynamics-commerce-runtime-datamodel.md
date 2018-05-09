---
title: HardwareProfile.FiscalPrinterManagementReportGiftCard Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FiscalPrinterManagementReportGiftCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.FiscalPrinterManagementReportGiftCard
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.fiscalprintermanagementreportgiftcard(v=AX.60)
ms:contentKeyID: 62204721
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.FiscalPrinterManagementReportGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# FiscalPrinterManagementReportGiftCard Property

Gets or sets the gift card for fiscal printer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FISCALPRINTERTOTALIZERGIFTCARD_BR")> _
<DataMemberAttribute> _
Public Property FiscalPrinterManagementReportGiftCard As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.FiscalPrinterManagementReportGiftCard

instance.FiscalPrinterManagementReportGiftCard = value
```

``` csharp
[ColumnAttribute("FISCALPRINTERTOTALIZERGIFTCARD_BR")]
[DataMemberAttribute]
public string FiscalPrinterManagementReportGiftCard { get; set; }
```

``` c++
[ColumnAttribute(L"FISCALPRINTERTOTALIZERGIFTCARD_BR")]
[DataMemberAttribute]
public:
property String^ FiscalPrinterManagementReportGiftCard {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The gift card.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

