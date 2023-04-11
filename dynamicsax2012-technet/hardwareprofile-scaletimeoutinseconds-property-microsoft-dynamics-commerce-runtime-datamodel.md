---
title: HardwareProfile.ScaleTimeoutInSeconds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ScaleTimeoutInSeconds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.ScaleTimeoutInSeconds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.scaletimeoutinseconds(v=AX.60)
ms:contentKeyID: 62208697
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.ScaleTimeoutInSeconds
dev_langs:
- CSharp
- C++
- VB
---

# ScaleTimeoutInSeconds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the scale timeout in seconds.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TIMEOUTINSEC")> _
<DataMemberAttribute> _
Public Property ScaleTimeoutInSeconds As Integer
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Integer

value = instance.ScaleTimeoutInSeconds

instance.ScaleTimeoutInSeconds = value
```

``` csharp
[ColumnAttribute("TIMEOUTINSEC")]
[DataMemberAttribute]
public int ScaleTimeoutInSeconds { get; set; }
```

``` c++
[ColumnAttribute(L"TIMEOUTINSEC")]
[DataMemberAttribute]
public:
property int ScaleTimeoutInSeconds {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The timeout value.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

