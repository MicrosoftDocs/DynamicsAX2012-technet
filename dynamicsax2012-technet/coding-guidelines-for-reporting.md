---
title: Coding Guidelines for Reporting
TOCTitle: Coding Guidelines for Reporting
ms:assetid: 62f0dd69-807f-4c79-a509-ad3a468062b8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn249346(v=AX.60)
ms:contentKeyID: 54749596
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Coding Guidelines for Reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic contains coding guidelines to follow when creating Microsoft Dynamics AX reports.

## Use identifierStr to validate parameter names

The [identifierStr Function](https://technet.microsoft.com/en-us/library/aa865105\(v=ax.60\)) is used to convert an identifier into a string, and validates that its argument is a valid identifier.  A benefit of using this function is that we don’t need to put the string in quotes like ‘BookId’; instead we can simply use identifierStr(BookId).

This method is mainly used in the contract class, for the parm methods.  For example, the parm method can be decorated with the DataMemberAttribute attribute which specifies the parameter name.

  This can be specified using the identifierStr() method as follows:

    // correct
    DataMemberAttribute(identifierStr(DocumentDate))
    // incorrect
    DataMemberAttribute(‘DocumentDate’)

## Use literalStr to validate label strings

The [literalStr Function](https://technet.microsoft.com/en-us/library/aa876886\(v=ax.60\)) is used to validate a string at compile time.  The parameter can either be a hard coded string (in which case, a best practices error for a hard coded string will be thrown) or, as is more often the case, a label ID.  The main benefit of using this method is that it validates the label ID passed to it at compile time and throws a best practices error if an invalid label ID is passed to it.

This method is also often used in the contract class, for the parm methods. For example, the parm method can be decorated with [SysOperationLabelAttribute](https://technet.microsoft.com/en-us/library/gg963117\(v=ax.60\)) attribute which specifies the label for the parameter.

This can be specified using the literalStr() method as follows:

    SysOperationLabelAttribute (literalStr ("@SYS95927"))   // Correct
    SysOperationLabelAttribute ("@SYS95927")    // Incorrect

## Use ssrsReportStr to specify the report to be run by a Controller Class

Similar to the [identifierStr Function](https://technet.microsoft.com/en-us/library/aa865105\(v=ax.60\)) and [literalStr Function](https://technet.microsoft.com/en-us/library/aa876886\(v=ax.60\)), the [ssrsReportStr Function](https://technet.microsoft.com/en-us/library/dn250992\(v=ax.60\)) parses the 2 values passed to it – the report name and the design name – to validate whether it represents a valid report or not.  The report name needs to be set when a menu item points to a controller so that the controller knows which report-design combination must be invoked.  Using the [ssrsReportStr Function](https://technet.microsoft.com/en-us/library/dn250992\(v=ax.60\)) provides the benefit of compile time validation for the report and design name.  The report name can be specified using the [ssrsReportStr Function](https://technet.microsoft.com/en-us/library/dn250992\(v=ax.60\)) as follows:

    controller.parmReportName(ssrsReportStr(ReportName,DesignName));

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

