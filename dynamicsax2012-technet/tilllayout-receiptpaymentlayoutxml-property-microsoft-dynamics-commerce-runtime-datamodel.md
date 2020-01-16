---
title: TillLayout.ReceiptPaymentLayoutXml Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptPaymentLayoutXml Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.ReceiptPaymentLayoutXml
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.receiptpaymentlayoutxml(v=AX.60)
ms:contentKeyID: 62203275
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.ReceiptPaymentLayoutXml
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptPaymentLayoutXml Property

Gets or sets the value of receipt payment xml.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RECEIPTPAYMENTLAYOUTXML")> _
<DataMemberAttribute> _
Public Property ReceiptPaymentLayoutXml As String
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As String

value = instance.ReceiptPaymentLayoutXml

instance.ReceiptPaymentLayoutXml = value
```

``` csharp
[ColumnAttribute("RECEIPTPAYMENTLAYOUTXML")]
[DataMemberAttribute]
public string ReceiptPaymentLayoutXml { get; set; }
```

``` c++
[ColumnAttribute(L"RECEIPTPAYMENTLAYOUTXML")]
[DataMemberAttribute]
public:
property String^ ReceiptPaymentLayoutXml {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The receipt payment xml.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

