---
title: TenderLineBase.SignatureData Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SignatureData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.SignatureData
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.signaturedata(v=AX.60)
ms:contentKeyID: 62211998
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.SignatureData
dev_langs:
- CSharp
- C++
- VB
---

# SignatureData Property

Gets or sets the signature capture data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SIGNATUREDATA")> _
Public Property SignatureData As String
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As String

value = instance.SignatureData

instance.SignatureData = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SIGNATUREDATA")]
public string SignatureData { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SIGNATUREDATA")]
public:
property String^ SignatureData {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

