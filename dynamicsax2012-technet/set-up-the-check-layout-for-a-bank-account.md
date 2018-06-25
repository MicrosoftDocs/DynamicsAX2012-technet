---
title: Set up the check layout for a bank account
TOCTitle: Set up the check layout for a bank account
ms:assetid: 23e4e430-0135-431c-9c8e-18181169f3fb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg230993(v=AX.60)
ms:contentKeyID: 36676375
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up the check layout for a bank account [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to specify the position of a default check format on a page, and how to include up to two slip copies on the page. Slip copies are also known as check stubs. Use the **Check layout** form to set up the check layout that is used for a bank account.


> [!TIP]
> <P>The <STRONG>Check layout</STRONG> form controls the vertical position of the whole default check layout on the page. To move individual fields in the default check layout, a developer must customize the check report. For more information about how to customize reports, see <A href="report-integration-and-customization-overview.md">Report Integration and Customization Overview</A>.</P>



1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select a bank account.

3.  On the **Action Pane**, on the **Set up** tab, click **Check**.

4.  In the **Check layout** form, select the method to use for generating check numbers.

5.  In the **Check form** field, select the check format in which checks will be printed.

6.  Enter information in the **Paper length**, **Check start position**, and **Number of slip copies** fields to determine the position of the default check format on the page. The following illustration shows examples of how these fields work together.
    
    ![Examples of check layout configurations](images/Gg230993.CheckLayoutExamples(AX.60).png "Examples of check layout configurations")

7.  Click **Print test**.

8.  In the **Check layout - print test** form, select the type of check to print: negotiable or non-negotiable. For more information, see [Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md).

9.  If necessary, click **Options**, select a printer, and then click **OK**.

10. In the **Check layout - print test** form, click **OK** to print a test copy of the check layout on plain paper.

11. Compare the test copy of the check layout to the preprinted check stock that you use. Put the plain-paper test copy over the preprinted check stock, and hold both up to a window or other light source. Use a ruler to measure the difference between where the default check format is printed and where it should be printed.

12. Repeat steps 6 through 11 until you are satisfied with the vertical position of the check and slip copies.

## See also

[Check layout (form)](https://technet.microsoft.com/en-us/library/aa576973\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

