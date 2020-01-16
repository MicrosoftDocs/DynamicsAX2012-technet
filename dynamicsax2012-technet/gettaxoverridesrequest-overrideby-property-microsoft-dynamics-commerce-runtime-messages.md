---
title: GetTaxOverridesRequest.OverrideBy Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OverrideBy Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetTaxOverridesRequest.OverrideBy
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.gettaxoverridesrequest.overrideby(v=AX.60)
ms:contentKeyID: 62214722
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetTaxOverridesRequest.OverrideBy
dev_langs:
- CSharp
- C++
- VB
---

# OverrideBy Property

Gets or sets the overrideby.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OverrideBy As TaxOverrideBy
    Get
    Set
'Usage
Dim instance As GetTaxOverridesRequest
Dim value As TaxOverrideBy

value = instance.OverrideBy

instance.OverrideBy = value
```

``` csharp
[DataMemberAttribute]
public TaxOverrideBy OverrideBy { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property TaxOverrideBy OverrideBy {
    TaxOverrideBy get ();
    void set (TaxOverrideBy value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy](taxoverrideby-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The overrideby.  

## See Also

#### Reference

[GetTaxOverridesRequest Class](gettaxoverridesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

