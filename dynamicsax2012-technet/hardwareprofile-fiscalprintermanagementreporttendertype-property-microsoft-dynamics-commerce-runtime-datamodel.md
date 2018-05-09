---
title: HardwareProfile.FiscalPrinterManagementReportTenderType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FiscalPrinterManagementReportTenderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.FiscalPrinterManagementReportTenderType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.fiscalprintermanagementreporttendertype(v=AX.60)
ms:contentKeyID: 62206725
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.FiscalPrinterManagementReportTenderType
dev_langs:
- CSharp
- C++
- VB
---

# FiscalPrinterManagementReportTenderType Property

Gets or sets the tender type for fiscal printer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FISCALPRINTERMGMTREPORTTENDERTYPE_BR")> _
Public Property FiscalPrinterManagementReportTenderType As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.FiscalPrinterManagementReportTenderType

instance.FiscalPrinterManagementReportTenderType = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FISCALPRINTERMGMTREPORTTENDERTYPE_BR")]
public string FiscalPrinterManagementReportTenderType { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FISCALPRINTERMGMTREPORTTENDERTYPE_BR")]
public:
property String^ FiscalPrinterManagementReportTenderType {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The tender type.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

