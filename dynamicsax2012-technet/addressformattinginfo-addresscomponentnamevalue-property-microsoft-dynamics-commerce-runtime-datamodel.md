---
title: AddressFormattingInfo.AddressComponentNameValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddressComponentNameValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.AddressComponentNameValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.addressformattinginfo.addresscomponentnamevalue(v=AX.60)
ms:contentKeyID: 65320359
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.AddressComponentNameValue
dev_langs:
- CSharp
- C++
- VB
---

# AddressComponentNameValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AddressComponentNameValue As Integer
    Get
    Set
'Usage
Dim instance As AddressFormattingInfo
Dim value As Integer

value = instance.AddressComponentNameValue

instance.AddressComponentNameValue = value
```

``` csharp
[DataMemberAttribute]
public int AddressComponentNameValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int AddressComponentNameValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[AddressFormattingInfo Class](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

