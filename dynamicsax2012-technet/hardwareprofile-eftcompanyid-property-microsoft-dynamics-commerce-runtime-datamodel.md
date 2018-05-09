---
title: HardwareProfile.EftCompanyId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EftCompanyId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EFTCompanyId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.eftcompanyid(v=AX.60)
ms:contentKeyID: 62209869
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EftCompanyId
dev_langs:
- CSharp
- C++
- VB
---

# EftCompanyId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EFTCOMPANYID")> _
<DataMemberAttribute> _
Public Property EftCompanyId As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.EftCompanyId

instance.EftCompanyId = value
```

``` csharp
[ColumnAttribute("EFTCOMPANYID")]
[DataMemberAttribute]
public string EftCompanyId { get; set; }
```

``` c++
[ColumnAttribute(L"EFTCOMPANYID")]
[DataMemberAttribute]
public:
property String^ EftCompanyId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

