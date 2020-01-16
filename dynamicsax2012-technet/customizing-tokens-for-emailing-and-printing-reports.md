---
title: Customizing tokens for emailing and printing reports
TOCTitle: Customizing tokens for emailing and printing reports
ms:assetid: e756e8d0-95f8-49ed-bd4a-8b4ff88d08f2
ms:mtpsurl: https://technet.microsoft.com/library/Dn479194(v=AX.60)
ms:contentKeyID: 59633684
author: Khairunj
ms.date: 01/08/2014
mtps_version: v=AX.60
---

# Customizing tokens for emailing and printing reports 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

In cumulative update 7 or later for Microsoft Dynamics AX 2012 R2, you can email reports to specific people by using tokens in the **Print destination settings** form. Tokens are strings delimited with @ signs, such as **@\<Job Title\>@** or **@\<Purpose\>@**, that you can use instead of entering individual email addresses. Built-in functionality in cumulative update 7 or later for Microsoft Dynamics AX 2012 R2 lets you use tokens like **@Staffing Specialist@** or <strong>@Billing@</strong> to send a report to all workers with a particular job title or customer contacts with a particular purpose.

Reports that use print management that are intended for an external audience support both worker title tokens and customer/vendor purpose tokens. Reports that don’t use print management and are intended for an internal audience support only the worker title tokens.

Developers can also customize the functionality of the tokens used in the **Print destination settings** form for emailing reports to a list. For example, you can develop an additional customization to retrieve titles from an external address book and send a report to the list of addresses that is retrieved externally. You can also customize tokens to specify other print destinations by using print management. For example, you can use tokens to specify a printer based on location. In this scenario, a token such as **@wh printer@** could be used to specify a warehouse printer.

## Customizing token functionality

To customize the token functionality, use the [extension framework](http://blogs.msdn.com/b/ax_gfm_framework_team_blog/archive/2012/11/13/the-microsoft-dynamics-ax-2012-extension-framework-part-1.aspx) to create a class that extends the SRSPrintDestinationToken class.

For example, the following class declaration uses the SrsPrintDestinationTokensExtAttribute to indicate a custom class type to the framework.

    [SrsPrintDestinationTokensExtAttribute('Custom')]
    class CustomPrintDestinationTokens extends SrsPrintDestinationTokens
    {
        //…
    }

To understand how to customize or extend the functionality for processing tokens, you should first understand how the framework classes supplied for this purpose work.

The following classes for expanding tokens into email addresses all extend SRSPrintDestinationToken:

1.  PrintMgmtPrintDestinationTokens class handles contact purpose support for printer destination tokens.

2.  HcmWorkerPrintDestinationTokens class handles worker title support for printer destination tokens.

3.  **SRSPrintDestinationNone** handles non-token cases like regular email addresses.

These classes are chained together in the order above, so that if one class doesn’t recognize a type of token, it is passed on to the next class in the chain. Each class specifies the next link in the chain in its new method.

For external reports, which use print management, PrintMgmtPrintDestinationTokens is the first class in the chain. For internal reports, the chain starts with HcmWorkerPrintDestinationTokens.

The **expandEmailToken** method in **PrintMgmtPrintDestinationTokens** provides an example of how to pass a token onto the next link in the processing chain. If you develop a custom class to do your own token processing, it should work properly with the other classes in the chain.

## How to use tokens in the print destination settings form

For more information about how to insert tokens when you send a report as email, see [Print or email a report](print-or-email-a-report.md).

## See also

[Print Management Integration Guide](print-management-integration-guide.md)

[Print or email a report](print-or-email-a-report.md)

