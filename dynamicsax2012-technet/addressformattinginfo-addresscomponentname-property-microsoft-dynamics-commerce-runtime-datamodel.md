---
title: AddressFormattingInfo.AddressComponentName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddressComponentName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.AddressComponentName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.addressformattinginfo.addresscomponentname(v=AX.60)
ms:contentKeyID: 49821267
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.AddressComponentName
dev_langs:
- CSharp
- C++
- VB
---

# AddressComponentName Property

Gets or sets the name of the address component.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ELEMENT")> _
<IgnoreDataMemberAttribute> _
Public Property AddressComponentName As AddressFormatLineType
    Get
    Set
'Usage
Dim instance As AddressFormattingInfo
Dim value As AddressFormatLineType

value = instance.AddressComponentName

instance.AddressComponentName = value
```

``` csharp
[ColumnAttribute("ELEMENT")]
[IgnoreDataMemberAttribute]
public AddressFormatLineType AddressComponentName { get; set; }
```

``` c++
[ColumnAttribute(L"ELEMENT")]
[IgnoreDataMemberAttribute]
public:
property AddressFormatLineType AddressComponentName {
    AddressFormatLineType get ();
    void set (AddressFormatLineType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType](addressformatlinetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The name of the address component.  

## Remarks

Street, City etc.

## See Also

#### Reference

[AddressFormattingInfo Class](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

