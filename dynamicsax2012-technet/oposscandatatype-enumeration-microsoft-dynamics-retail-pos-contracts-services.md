---
title: OPOSScanDataType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: OPOSScanDataType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.oposscandatatype(v=AX.60)
ms:contentKeyID: 47344083
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_Code39
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_UPCD4
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_EAN128
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_PDF417
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_UPCE
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_EAN13_S
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_OCRB
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_UPCD3
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_ITF
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_Code128
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_UPCA_S
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_EAN13
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_MAXICODE
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_UNKNOWN
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_EAN8_S
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_UPCD1
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_UPCA
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_Code93
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_TF
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_EAN8
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_Codabar
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_OTHER
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_UPCD2
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_JAN13
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_UPCD5
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_UPCE_S
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_JAN8
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType.SCAN_SDT_OCRA
dev_langs:
- CSharp
- C++
- VB
---

# OPOSScanDataType Enumeration

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.OPOSScanDataType interface specifies the data type that is scanned using an OPOS device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration OPOSScanDataType
'Usage
Dim instance As OPOSScanDataType
```

``` csharp
public enum OPOSScanDataType
```

``` c++
public enum class OPOSScanDataType
```

## Members

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>SCAN_SDT_UPCA</td>
<td>Digits</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_UPCE</td>
<td>Digits</td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_JAN8</td>
<td>EAN 8</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_EAN8</td>
<td>JAN 8 (added in 1.2)</td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_JAN13</td>
<td>EAN 13</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_EAN13</td>
<td>JAN 13 (added in 1.2)</td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_TF</td>
<td>(Discrete 2 of 5) Digits</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_ITF</td>
<td>(Interleaved 2 of 5) Digits</td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_Codabar</td>
<td>Digits, -, $, :, /, ., +; 4 start/stop characters (a, b, c, d)</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_Code39</td>
<td>Alpha, Digits, Space, -, ., $, /, +, %; start/stop (*). Also has Full ASCII feature</td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_Code93</td>
<td>Same characters as Code 39</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_Code128</td>
<td>128 data characters</td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_UPCA_S</td>
<td>UPC-A with supplemental barcode</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_UPCE_S</td>
<td>UPC-E with supplemental barcode</td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_UPCD1</td>
<td>UPC-D1</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_UPCD2</td>
<td>UPC-D2</td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_UPCD3</td>
<td>UPC-D3</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_UPCD4</td>
<td>UPC-D4</td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_UPCD5</td>
<td>UPC-D5</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_EAN8_S</td>
<td>EAN 8 with supplemental barcode</td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_EAN13_S</td>
<td>EAN 13 with supplemental barcode</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_EAN128</td>
<td>EAN 128</td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_OCRA</td>
<td>OCR &quot;A&quot;</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_OCRB</td>
<td>OCR &quot;B&quot;</td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_PDF417</td>
<td>Two-dimensional symbology: 201
<p>Not supported by AX or POS</p></td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_MAXICODE</td>
<td>Two-dimensional symbology: 202
<p>Not supported by AX or POS</p></td>
</tr>
<tr class="odd">
<td></td>
<td>SCAN_SDT_OTHER</td>
<td>Special case: start of Scanner-Specific bar</td>
</tr>
<tr class="even">
<td></td>
<td>SCAN_SDT_UNKNOWN</td>
<td>Special cases: cannot determine the barcode</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

