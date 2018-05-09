---
title: AttributeNameTranslation.FriendlyName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FriendlyName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeNameTranslation.FriendlyName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.attributenametranslation.friendlyname(v=AX.60)
ms:contentKeyID: 49854390
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeNameTranslation.FriendlyName
dev_langs:
- CSharp
- C++
- VB
---

# FriendlyName Property

Gets or sets the translation text.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FRIENDLYNAME")> _
Public Property FriendlyName As String
    Get
    Set
'Usage
Dim instance As AttributeNameTranslation
Dim value As String

value = instance.FriendlyName

instance.FriendlyName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FRIENDLYNAME")]
public string FriendlyName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FRIENDLYNAME")]
public:
property String^ FriendlyName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The name of the friendly.  

## See Also

#### Reference

[AttributeNameTranslation Class](attributenametranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

