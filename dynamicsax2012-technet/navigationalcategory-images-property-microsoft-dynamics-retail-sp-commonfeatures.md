---
title: NavigationalCategory.Images Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: Images Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.Images
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.navigationalcategory.images(v=AX.60)
ms:contentKeyID: 62203877
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.Images
dev_langs:
- CSharp
- C++
- VB
---

# Images Property

Gets the images.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Property Images As IList(Of String)
    Get
    Private Set
'Usage
Dim instance As NavigationalCategory
Dim value As IList(Of String)

value = instance.Images
```

``` csharp
public IList<string> Images { get; private set; }
```

``` c++
public:
property IList<String^>^ Images {
    IList<String^>^ get ();
    private: void set (IList<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
The images.  

## See Also

#### Reference

[NavigationalCategory Class](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

