---
title: TenderLineBase.TenderTypeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderTypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.TenderTypeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.tendertypeid(v=AX.60)
ms:contentKeyID: 62208691
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.TenderTypeId
dev_langs:
- CSharp
- C++
- VB
---

# TenderTypeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tender type identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TENDERTYPEID")> _
<DataMemberAttribute> _
Public Property TenderTypeId As String
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As String

value = instance.TenderTypeId

instance.TenderTypeId = value
```

``` csharp
[ColumnAttribute("TENDERTYPEID")]
[DataMemberAttribute]
public string TenderTypeId { get; set; }
```

``` c++
[ColumnAttribute(L"TENDERTYPEID")]
[DataMemberAttribute]
public:
property String^ TenderTypeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The type of the tender.  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

