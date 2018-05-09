---
title: 'How to: Create a Company Parameter in a Report'
TOCTitle: 'How to: Create a Company Parameter in a Report'
ms:assetid: cb6e7bb6-1dc6-4745-b8aa-e45553bde9fe
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh533448(v=AX.60)
ms:contentKeyID: 39056464
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Create a Company Parameter in a Report 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to create a parameter to control the data for a report based on a company. On a report, parameters are used to filter data, control appearance, and connect to related reports. When you create a company report parameter for a report, and then run that report, you enable the user to choose the company on which the report data will be based.You will use the AX\_CompanyName parameter that is added to a report model by the reporting framework when you add a dataset bound to a data source. The AX\_CompanyName parameter is a mandatory framework parameter. The parameter cannot be null, cannot be blank, and has the following default value =Microsoft.Dynamics.Framework.Reports.BuiltInMethods.GetUserCompany(Parameters\!AX\_UserContext.Value). The following steps describe how to use the AX\_CompanyName parameter to filter data based on company.

### To create a company parameter in a report

1.  In Visual Studio, open the reporting project.

2.  In Model Editor, expand the node for the report that you want to work with.

3.  Expand the **Parameters** node for the report, and then select the **AX\_CompanyName** parameter. The **AX\_CompanyName** parameter is added by the reporting framework after you bind the dataset to a data source.

4.  In the Properties window, set the **Visibility** property to **Visible**.

Next, you can create a design in your report model and then deploy the report to see the company parameter. For more information, see [How to: Create an Auto Design for a Report](how-to-create-an-auto-design-for-a-report.md).

## See also

[Working with Parameters](working-with-parameters.md)

