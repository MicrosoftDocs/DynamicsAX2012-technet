---
title: LogOnType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogOnType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.logontype(v=AX.60)
ms:contentKeyID: 62210860
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType.BarcodeReader
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType.MagneticCardReader
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType.PasswordWithNoDevice
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType
dev_langs:
- CSharp
- C++
- VB
---

# LogOnType Enumeration

Represents the type of logon type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration LogOnType
'Usage
Dim instance As LogOnType
```

``` csharp
[DataContractAttribute]
public enum LogOnType
```

``` c++
[DataContractAttribute]
public enum class LogOnType
```

## Members

<table>
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
<td>None</td>
<td>No LogOn type specified.</td>
</tr>
<tr class="even">
<td></td>
<td>BarcodeReader</td>
<td>Bar code Logon.</td>
</tr>
<tr class="odd">
<td></td>
<td>MagneticCardReader</td>
<td>Magnetic Card Reader Logon.</td>
</tr>
<tr class="even">
<td></td>
<td>PasswordWithNoDevice</td>
<td>Password with no device.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

