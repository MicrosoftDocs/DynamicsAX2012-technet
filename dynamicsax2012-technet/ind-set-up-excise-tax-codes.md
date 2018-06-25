---
title: (IND) Set up excise tax codes
TOCTitle: (IND) Set up excise tax codes
ms:assetid: 5a7ac4ba-2b50-4769-9751-cb40a60a0c1b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677839(v=AX.60)
ms:contentKeyID: 49385805
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Set up excise tax codes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must create the excise tax codes for the excise duties that your company must calculate and pay to the excise authorities. Specify the percentage for the calculation of excise for an excise tax code in the **Values** from of the **Sales tax codes** form. (Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**. Click **Values**.)


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Press CTRL+N and enter required details for a new tax code.

3.  Select **Excise** in the **Tax type** field.

4.  Enter the code that identifies the excise tax in the **Sales tax code** field.

5.  Enter the name for the excise tax code in the **Name** field.

6.  Select the code name used when identifying the sales tax settlement period in the **Settlement period** field.

7.  Select the excise tax ledger posting group for the excise tax code in the **Tax ledger posting group** field.

8.  Select a method of calculation in the **Origin** field to calculate the excise duty. The method of calculation is applied to the base amount of the tax.
    

    > [!NOTE]
    > <P><STRONG>Percentage of net amount</STRONG> and <STRONG>Amount per unit</STRONG> are the two calculation methods that you can use for the <STRONG>Excise</STRONG> tax type.</P>



9.  You can view the percentage or the amount in the **Percentage/Amount** field that is specified for the excise tax code in the **Values of sales tax codes** form.

10. Click the **General** tab.

11. Select the excise tax component that must be attached to the excise tax code in the **Tax component** field.

12. Click **Values** to open the **Values of sales tax codes** form.
    

    > [!NOTE]
    > <P>For more information, see "Values of sales tax codes (form)" in the Applications and Business Processes Help.</P>



13. Select the excise tariff code that the excise rates are defined for in the **Tariff code** field.

14. Enter the starting and ending dates of the validity period for the excise tax values in the **From date** and **To date** fields.

15. Specify the lower and upper limits for the excise tax calculation in the **Minimum limit** and **Upper limit** fields.
    

    > [!NOTE]
    > <P>Enter the value in as a percentage in the <STRONG>Minimum limit</STRONG> field and in the <STRONG>Upper limit</STRONG> field. It is not mandatory to enter values in these fields.</P>



16. Enter the value in as a percentage of the excise tax in the **Value** field.

17. Enter the concessional value for excise for the Small Scale Industry (SSI) vendors in the **Concessional value** field.

18. Press CTRL+S or close the form.

## See also

[(IND) Sales tax codes (modified form)](https://technet.microsoft.com/en-us/library/jj664864\(v=ax.60\))

[(IND) Values of sales tax codes (modified form)](https://technet.microsoft.com/en-us/library/jj664855\(v=ax.60\))

[(IND) Set up excise settlement periods](ind-set-up-excise-settlement-periods.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

