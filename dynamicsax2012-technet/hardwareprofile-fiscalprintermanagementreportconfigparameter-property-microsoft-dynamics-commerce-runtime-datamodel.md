---
title: HardwareProfile.FiscalPrinterManagementReportConfigParameter Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FiscalPrinterManagementReportConfigParameter Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.FiscalPrinterManagementReportConfigParameter
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.fiscalprintermanagementreportconfigparameter(v=AX.60)
ms:contentKeyID: 62204241
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.FiscalPrinterManagementReportConfigParameter
dev_langs:
- CSharp
- C++
- VB
---

# FiscalPrinterManagementReportConfigParameter Property

Gets or sets the config parameters for fiscal printer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FISCALPRINTERMGMTREPORTCONFIGPARAM_BR")> _
<DataMemberAttribute> _
Public Property FiscalPrinterManagementReportConfigParameter As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.FiscalPrinterManagementReportConfigParameter

instance.FiscalPrinterManagementReportConfigParameter = value
```

``` csharp
[ColumnAttribute("FISCALPRINTERMGMTREPORTCONFIGPARAM_BR")]
[DataMemberAttribute]
public string FiscalPrinterManagementReportConfigParameter { get; set; }
```

``` c++
[ColumnAttribute(L"FISCALPRINTERMGMTREPORTCONFIGPARAM_BR")]
[DataMemberAttribute]
public:
property String^ FiscalPrinterManagementReportConfigParameter {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The config parameters.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

