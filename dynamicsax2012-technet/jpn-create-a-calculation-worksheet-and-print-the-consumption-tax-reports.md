---
title: (JPN) Create a calculation worksheet and print the consumption tax reports
TOCTitle: (JPN) Create a calculation worksheet and print the consumption tax reports
ms:assetid: a57449da-7ad9-4cec-aa51-44907c6b588b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711215(v=AX.60)
ms:contentKeyID: 49386527
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- JP - 00004
---

# (JPN) Create a calculation worksheet and print the consumption tax reports [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The Japanese taxation authority requires that businesses file a consumption tax report that consists of an official consumption tax form and a worksheet. You can print the official tax form and use the calculation sheet to calculate the values that are required for the official tax form. The dates on the tax reports are displayed in the Japanese era format.

1.  Click **General ledger** \> **Reports** \> **External** \> **Japanese sales tax report**.

2.  In the **Consumption tax working sheet** form, select the settlement period for the consumption tax in the **Settlement period** field.

3.  Enter or select the starting date and ending date in the **From date** and **To date** fields.
    

    > [!NOTE]
    > <P>In the <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields, you must enter the corresponding dates of the settlement period that you selected in the <STRONG>Settlement period</STRONG> field.</P>



4.  Select the declaration type in the **Type of declaration** field. The options are:
    
      - **Interim** – Report declared for an interim period.
    
      - **Final** – Final report.
    

    > [!NOTE]
    > <P>If you select <STRONG>Interim</STRONG> in the <STRONG>Type of declaration</STRONG> field, the calculation is based on the dates in the <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields. If you select <STRONG>Final</STRONG> in the <STRONG>Type of declaration</STRONG> field, the calculation is based on the dates in the <STRONG>Settlement period</STRONG> field.</P>



5.  Select the calculation method in the **Calculation method** field from the following options:
    
      - **Individual method**
    
      - **Lumpsum method**

6.  Select the **Amendment** check box to print the amendment report for the final or interim report.

7.  Click **OK** to open the **Consumption tax calculation sheet** form.

8.  Verify the displayed calculated amounts and modify the information in the fields in the **Consumption tax calculation sheet form**, if needed.
    

    > [!NOTE]
    > <P>If you select a period that the tax reports are submitted in, select <STRONG>Consumption tax calculation</STRONG> to view the data that was submitted earlier.</P>



9.  Click **Functions** \> **Update amount** to recalculate the amounts, based on the amounts entered manually.

10. Click **Functions** \> **Finalize** after you confirm the data.

11. Click **Functions** \> **Consumption tax report** to open the **Consumption tax report** form.
    

    > [!NOTE]
    > <P>The <STRONG>Consumption tax report</STRONG> option is available only if you finalize the calculations.</P>



12. In the **Consumption tax** report, verify the tax information and modify the details, if required.

13. Click **Functions** \> **Finalize** after you have confirmed the data.

14. Click **Functions** \> **Print report** to print the **Consumption tax** report.
    

    > [!NOTE]
    > <P>The <STRONG>Print report</STRONG> option is available only if you finalize the calculations.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

