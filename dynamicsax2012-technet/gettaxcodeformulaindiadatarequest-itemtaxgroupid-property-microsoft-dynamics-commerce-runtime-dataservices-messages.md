---
title: GetTaxCodeFormulaIndiaDataRequest.ItemTaxGroupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ItemTaxGroupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeFormulaIndiaDataRequest.ItemTaxGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.gettaxcodeformulaindiadatarequest.itemtaxgroupid(v=AX.60)
ms:contentKeyID: 65319686
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeFormulaIndiaDataRequest.ItemTaxGroupId
dev_langs:
- CSharp
- C++
- VB
---

# ItemTaxGroupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item tax group identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemTaxGroupId As String
    Get
    Private Set
'Usage
Dim instance As GetTaxCodeFormulaIndiaDataRequest
Dim value As String

value = instance.ItemTaxGroupId
```

``` csharp
[DataMemberAttribute]
public string ItemTaxGroupId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ItemTaxGroupId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetTaxCodeFormulaIndiaDataRequest Class](gettaxcodeformulaindiadatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

