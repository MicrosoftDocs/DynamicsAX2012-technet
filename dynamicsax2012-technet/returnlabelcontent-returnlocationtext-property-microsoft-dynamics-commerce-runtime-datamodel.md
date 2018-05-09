---
title: ReturnLabelContent.ReturnLocationText Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnLocationText Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReturnLabelContent.ReturnLocationText
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.returnlabelcontent.returnlocationtext(v=AX.60)
ms:contentKeyID: 65322402
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReturnLabelContent.ReturnLocationText
dev_langs:
- CSharp
- C++
- VB
---

# ReturnLocationText Property

Gets or sets the return location text.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReturnLocationText As String
    Get
    Set
'Usage
Dim instance As ReturnLabelContent
Dim value As String

value = instance.ReturnLocationText

instance.ReturnLocationText = value
```

``` csharp
[DataMemberAttribute]
public string ReturnLocationText { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReturnLocationText {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The return location text, if any.  

## See Also

#### Reference

[ReturnLabelContent Class](returnlabelcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

