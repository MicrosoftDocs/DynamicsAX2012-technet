---
title: ZipCodeInfo.ZipPostalCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ZipPostalCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ZipCodeInfo.ZipPostalCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.zipcodeinfo.zippostalcode(v=AX.60)
ms:contentKeyID: 49841958
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ZipCodeInfo.ZipPostalCode
dev_langs:
- CSharp
- C++
- VB
---

# ZipPostalCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the zip/postal code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<KeyAttribute> _
<ColumnAttribute("ZIPCODE")> _
Public Property ZipPostalCode As String
    Get
    Set
'Usage
Dim instance As ZipCodeInfo
Dim value As String

value = instance.ZipPostalCode

instance.ZipPostalCode = value
```

``` csharp
[DataMemberAttribute]
[KeyAttribute]
[ColumnAttribute("ZIPCODE")]
public string ZipPostalCode { get; set; }
```

``` c++
[DataMemberAttribute]
[KeyAttribute]
[ColumnAttribute(L"ZIPCODE")]
public:
property String^ ZipPostalCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ZipCodeInfo Class](zipcodeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

