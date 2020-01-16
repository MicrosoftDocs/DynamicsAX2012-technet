---
title: HardwareProfile.FiscalPrinterManagementReportPAFIdentification Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FiscalPrinterManagementReportPAFIdentification Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.FiscalPrinterManagementReportPAFIdentification
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.fiscalprintermanagementreportpafidentification(v=AX.60)
ms:contentKeyID: 62207289
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.FiscalPrinterManagementReportPAFIdentification
dev_langs:
- CSharp
- C++
- VB
---

# FiscalPrinterManagementReportPAFIdentification Property

Gets or sets the PafEcfIndentification for fiscal printer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FISCALPRINTERMGMTREPORTPAFIDENTIFIC_BR")> _
Public Property FiscalPrinterManagementReportPAFIdentification As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.FiscalPrinterManagementReportPAFIdentification

instance.FiscalPrinterManagementReportPAFIdentification = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FISCALPRINTERMGMTREPORTPAFIDENTIFIC_BR")]
public string FiscalPrinterManagementReportPAFIdentification { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FISCALPRINTERMGMTREPORTPAFIDENTIFIC_BR")]
public:
property String^ FiscalPrinterManagementReportPAFIdentification {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The PafEcfIndentification.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

