---
title: GetUnitsOfMeasureRequest.UnitId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: UnitId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetUnitsOfMeasureRequest.UnitId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getunitsofmeasurerequest.unitid(v=AX.60)
ms:contentKeyID: 62208471
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetUnitsOfMeasureRequest.UnitId
dev_langs:
- CSharp
- C++
- VB
---

# UnitId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a specific unit symbol identifier to fetch.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UnitId As String
    Get
    Set
'Usage
Dim instance As GetUnitsOfMeasureRequest
Dim value As String

value = instance.UnitId

instance.UnitId = value
```

``` csharp
[DataMemberAttribute]
public string UnitId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ UnitId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Optional, if omitted all units of measure will be returned.

## See Also

#### Reference

[GetUnitsOfMeasureRequest Class](getunitsofmeasurerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

