---
title: ChannelPriceConfiguration.CompanyCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CompanyCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelPriceConfiguration.CompanyCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelpriceconfiguration.companycurrency(v=AX.60)
ms:contentKeyID: 62215126
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelPriceConfiguration.CompanyCurrency
dev_langs:
- CSharp
- C++
- VB
---

# CompanyCurrency Property

Gets or sets the collection of channel price groups to search by.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COMPANYCURRENCY")> _
<DataMemberAttribute> _
Public Property CompanyCurrency As String
    Get
    Set
'Usage
Dim instance As ChannelPriceConfiguration
Dim value As String

value = instance.CompanyCurrency

instance.CompanyCurrency = value
```

``` csharp
[ColumnAttribute("COMPANYCURRENCY")]
[DataMemberAttribute]
public string CompanyCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"COMPANYCURRENCY")]
[DataMemberAttribute]
public:
property String^ CompanyCurrency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelPriceConfiguration Class](channelpriceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

