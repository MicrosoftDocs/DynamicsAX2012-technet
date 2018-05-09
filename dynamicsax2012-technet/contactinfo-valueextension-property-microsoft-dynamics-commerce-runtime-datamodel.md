---
title: ContactInfo.ValueExtension Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValueExtension Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.ValueExtension
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.contactinfo.valueextension(v=AX.60)
ms:contentKeyID: 62212269
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.ValueExtension
dev_langs:
- CSharp
- C++
- VB
---

# ValueExtension Property

Gets or sets the extension for the value of the contact info.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LOCATOREXTENSION")> _
Public Property ValueExtension As String
    Get
    Set
'Usage
Dim instance As ContactInfo
Dim value As String

value = instance.ValueExtension

instance.ValueExtension = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LOCATOREXTENSION")]
public string ValueExtension { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LOCATOREXTENSION")]
public:
property String^ ValueExtension {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ContactInfo Class](contactinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

