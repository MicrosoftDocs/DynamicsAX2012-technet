---
title: GetTaxOverrideDetailsDataRequest.TaxOverrideCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: TaxOverrideCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxOverrideDetailsDataRequest.TaxOverrideCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.gettaxoverridedetailsdatarequest.taxoverridecode(v=AX.60)
ms:contentKeyID: 65320552
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxOverrideDetailsDataRequest.TaxOverrideCode
dev_langs:
- CSharp
- C++
- VB
---

# TaxOverrideCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax override code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TaxOverrideCode As String
    Get
    Private Set
'Usage
Dim instance As GetTaxOverrideDetailsDataRequest
Dim value As String

value = instance.TaxOverrideCode
```

``` csharp
[DataMemberAttribute]
public string TaxOverrideCode { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TaxOverrideCode {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetTaxOverrideDetailsDataRequest Class](gettaxoverridedetailsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

