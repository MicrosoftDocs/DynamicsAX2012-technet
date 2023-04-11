---
title: SalesLine.ElectronicDeliveryEmailContent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ElectronicDeliveryEmailContent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ElectronicDeliveryEmailContent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.electronicdeliveryemailcontent(v=AX.60)
ms:contentKeyID: 62211254
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ElectronicDeliveryEmailContent
dev_langs:
- CSharp
- C++
- VB
---

# ElectronicDeliveryEmailContent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the electronic Delivery Email Content.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ELECTRONICDELIVERYEMAILCONTENT")> _
Public Property ElectronicDeliveryEmailContent As String
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As String

value = instance.ElectronicDeliveryEmailContent

instance.ElectronicDeliveryEmailContent = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ELECTRONICDELIVERYEMAILCONTENT")]
public string ElectronicDeliveryEmailContent { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ELECTRONICDELIVERYEMAILCONTENT")]
public:
property String^ ElectronicDeliveryEmailContent {
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

