---
title: SalesLine.ElectronicDeliveryEmailAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ElectronicDeliveryEmailAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ElectronicDeliveryEmailAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.electronicdeliveryemailaddress(v=AX.60)
ms:contentKeyID: 62211156
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ElectronicDeliveryEmailAddress
dev_langs:
- CSharp
- C++
- VB
---

# ElectronicDeliveryEmailAddress Property

Gets or sets the electronic Delivery Email Address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ELECTRONICDELIVERYEMAIL")> _
<DataMemberAttribute> _
Public Property ElectronicDeliveryEmailAddress As String
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As String

value = instance.ElectronicDeliveryEmailAddress

instance.ElectronicDeliveryEmailAddress = value
```

``` csharp
[ColumnAttribute("ELECTRONICDELIVERYEMAIL")]
[DataMemberAttribute]
public string ElectronicDeliveryEmailAddress { get; set; }
```

``` c++
[ColumnAttribute(L"ELECTRONICDELIVERYEMAIL")]
[DataMemberAttribute]
public:
property String^ ElectronicDeliveryEmailAddress {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

