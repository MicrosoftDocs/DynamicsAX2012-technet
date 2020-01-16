---
title: Set up positive pay
TOCTitle: Set up positive pay
ms:assetid: c01ab305-6666-4857-8ee0-622a6c538d5d
ms:mtpsurl: https://technet.microsoft.com/library/Dn269119(v=AX.60)
ms:contentKeyID: 54920071
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- MenuItems.BankPositivePayFormat
audience: Application User
ms.search.region: Global
---

# Set up positive pay 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to help create a secure folder for positive pay files, set up an outbound port for positive pay files, set up a batch job to generate positive pay files, set up a number sequence for positive pay files, assign the positive pay format to bank accounts, and set up user security for positive pay.

Set up positive pay to generate an electronic list of checks that is provided to the bank. When the check is presented to the bank, the bank compares the check with the list of checks. If the check matches what the bank has on file in the list, the bank clears the check. If there is a difference, the bank holds the check for review.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for cumulative update 6 and cumulative update 7 for Microsoft Dynamics AX 2012 R2. This information applies to CU6, CU7, and later cumulative updates. This information also applies to AX 2012 R3.</P>



The following illustration shows how to set up positive pay. The numbers correspond to the procedures later in this topic.

![Positive pay setup process](images/Dn269119.SetUpPositivePay(AX.60).gif "Positive pay setup process")

## 1\. Create a secure folder for positive pay files

Positive pay files can contain sensitive information about payees and check amounts. Therefore, make sure that you use appropriate security measures from the time that the files are generated, until they are received by the bank. Consider the following security threats and mitigations.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Threat</p></th>
<th><p>Mitigation</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Unauthorized access to a folder and the data in the folder</p></td>
<td><p>Restrict access to the folder where the positive pay files are saved when they are generated. We recommend that you create one folder for each positive pay format, and use an Access Control List (ACL) to specify the domain users who can access each folder. For more information, see <a href="http://msdn.microsoft.com/en-us/library/windows/desktop/aa374872.aspx" class="uri">http://msdn.microsoft.com/en-us/library/windows/desktop/aa374872.aspx</a>.</p></td>
</tr>
<tr class="even">
<td><p>Data is sent to the folder through an unprotected network</p></td>
<td><p>Use a secured network.</p></td>
</tr>
<tr class="odd">
<td><p>Data is transferred to the bank</p></td>
<td><p>Use a secured system to transfer the positive pay file to the bank. For more information, contact your banking institution.</p></td>
</tr>
</tbody>
</table>


To set up a folder for positive pay files, follow these steps:

1.  In Windows Explorer, open the folder where you want to store positive pay files, such as **D:\\AX\\PositivePay** or a network location.

2.  Create a folder, such as **D:\\AX\\PositivePay\\Out**.

3.  In the folder that you started with in step 1, create another folder for the XSL transform file, such as **D:\\AX\\PositivePay\\BankXSLT**.

4.  Grant **Write** access for the **D:\\AX\\PositivePay** folder to the Microsoft Dynamics AX Application Object Server (AOS) service account. Don’t grant **Write** access to anyone else.

## 2\. Set up an outbound port for positive pay files

Positive pay files are created by using a service. Before you can generate a positive pay file, you must set up an outbound port for the positive pay service.


> [!NOTE]
> <P>You can’t change the XSLT file location or the outbound folder for an existing outbound port. Instead, you must create a new outbound port by following the steps in this procedure.</P>



To set up an outbound port for positive pay files, follow these steps:

1.  Log on to Microsoft Dynamics AX as a system administrator.

2.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Positive pay service** \> **Outbound ports for positive pay**.

3.  In the **Payment format** field, provide a format name, such as **PayFormat01**.

4.  In the **XSLT** field, select an XSL transform file that matches the format that is required by your bank. You must create the transform file. For example, the location of the XSLT file might be **D:\\AX\\PositivePay\\BankXSLT\\ExampleXSLT.xsl**.

5.  In the **Outbound folder** field, select the location where you want to save the positive pay files after they are transformed. For example, the location might be **D:\\AX\\PositivePay\\Out**.
    
    Make sure that the Microsoft Dynamics AX users who generate payments have **Write** access to this folder.

6.  Click **Create ports**. A message states that the port was deployed successfully.

## Example: XSLT file for positive pay files

    <?xml version="1.0" encoding="utf-8"?>
    <xsl:stylesheet version="1.0" xmlns:xsl="http://www.w3.org/1999/XSL/Transform"
        xmlns:msxsl="urn:schemas-microsoft-com:xslt" exclude-result-prefixes="msxsl s0 s1 xslthelper" xmlns="urn:iso:std:iso:20022:tech:xsd:pain.001.001.02"
                     xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xslthelper="http://schemas.microsoft.com/BizTalk/2003/xslthelper"
                    xmlns:s0="http://schemas.microsoft.com/dynamics/2008/01/sharedtypes" xmlns:s1="http://schemas.microsoft.com/dynamics/2008/01/documents/BankPositivePay"
                    >
    
      <xsl:template match="/">
        <xsl:apply-templates select="//s1:BankPositivePay"></xsl:apply-templates>
      </xsl:template>
      <xsl:template match="//s1:BankPositivePay">
        <Document>
          <xsl:value-of select="'&#13;&#10;'" />
          <xsl:for-each select="s1:BankAccountTable">
            <xsl:if test="count(child::s1:BankChequeTable) >0">
              <!--Header Begin-->
            <xsl:value-of select='string("Vendor ID,Vendor Name,Voided,Document Type,Check Date,Check Number,Check Amount,Checkbook ID,Vendor Class ID,Posted Date")'/>
            <xsl:value-of select="'&#13;&#10;'" />
            <!--Header End-->
            <!--Cheque Detail begin-->
            <xsl:for-each select="s1:BankChequeTable">
              <xsl:value-of select='s1:RecipientAccountNum/text()'/>
              <xsl:value-of select="'&#44;'" />
              <xsl:value-of select='s1:BankNegInstRecipientName/text()'/>
              <xsl:value-of select="'&#44;'" />
              <xsl:choose>
                <xsl:when test='s1:ChequeStatus/text()=normalize-space("Void") or s1:ChequeStatus/text()=normalize-space("Rejected") or s1:ChequeStatus/text()=normalize-space("Cancelled")'>
                  <xsl:value-of select='string("Yes")'/>
                </xsl:when>
                <xsl:when test='s1:ChequeStatus/text()=normalize-space("Payment")'>
                 <xsl:value-of select='string("No")'/>
                </xsl:when>
                <xsl:otherwise>
                  <xsl:value-of select='string(" ")'/>
                </xsl:otherwise>
              </xsl:choose>
              <xsl:value-of select="'&#44;'" />
              <xsl:value-of select='string("Payment")'/>
              <xsl:value-of select="'&#44;'" />
              <xsl:value-of select='s1:TransDate/text()'/>
              <xsl:value-of select="'&#44;'" />
              <xsl:value-of select='s1:ChequeNum/text()'/>
              <xsl:value-of select="'&#44;'" />
              <xsl:value-of select='s1:AmountCur/text()'/>
              <xsl:value-of select="'&#44;'" />
              <xsl:value-of select='string("BOA-#1812")'/>
              <xsl:value-of select="'&#44;'" />
              <xsl:choose>
              <xsl:when test='s1:RecipientType/text()=normalize-space("Vend")'>
              <xsl:for-each select="s1:VendTable">
                  <xsl:value-of select='s1:VendGroup/text()'/>
              </xsl:for-each>
              </xsl:when>
              <xsl:otherwise>
                  <xsl:for-each select="s1:CustTable">
                    <xsl:value-of select='s1:CustGroup/text()'/>
                  </xsl:for-each>
                </xsl:otherwise>
              </xsl:choose>
              <xsl:value-of select="'&#44;'" />
              <xsl:value-of select='s1:TransDate/text()'/>
              <xsl:value-of select="'&#13;&#10;'" />
              </xsl:for-each>
          </xsl:if>
          </xsl:for-each>
        </Document>
      </xsl:template>
    
      <msxsl:script language="C#" implements-prefix="xslthelper">
        <![CDATA[
        public string PadLeft(string value,int length,string paddingchar)
        {
          if(paddingchar!=String.Empty)
          {
            return value.PadLeft(length,(paddingchar.ToCharArray())[0]);
            }
            else
            {
              return value.PadLeft(length);
            }
        }
        public string FormatDate(string date)
        {
          DateTime dateTime=DateTime.Parse(date);
          if(dateTime!=null)
          {
          return dateTime.ToString("MMddyyyy");
          }
          else
          {
          return String.Empty;
          }
          
        }
        public int ConvertToInt(string s)
        {
          Double f=Convert.ToDouble(s);
          return (int)f;
        }
    ]]>
      </msxsl:script>
    </xsl:stylesheet>

## 3\. Set up a batch job to generate positive pay files

Set up a batch job that automatically processes the file that is created by the positive pay service. The batch job must also run the transform on the file so that it matches the format that is required by your bank. A batch job runs periodically. For more information, see [Create a batch job](create-a-batch-job.md).

1.  Log on to Microsoft Dynamics AX as an administrator.

2.  Switch to the legal entity that users will generate positive pay files from.

3.  Click **System administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

4.  Press Ctrl+N to create a batch job.

5.  In the **Job description** field, enter a description. For example, you might enter Generate positive pay files.

6.  Save the batch job.

7.  Click **View tasks**.

8.  Create the following tasks.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p><strong>Task description</strong></p></th>
    <th><p><strong>Company accounts</strong></p></th>
    <th><p>Class name</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>1</p></td>
    <td><p>Select the legal entity that users will generate positive pay files from.</p></td>
    <td><p><strong>AIFGatewaySendService</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>2</p></td>
    <td><p>Select the legal entity that users will generate positive pay files from.</p></td>
    <td><p><strong>AIFOutboundProcessingService</strong></p></td>
    </tr>
    </tbody>
    </table>


9.  Close the **Batch tasks** form.

10. In the **Batch job** form, select the batch that you created in steps 4 and 5, and then click **Recurrence**.

11. In the **Recurring pattern** field group, select **Minutes**. In the **Count** field, enter the number of minutes. For example, you might enter 1 to process payment files every one minute.

12. Click **OK** to close the **Recurrence** form.

13. In the **Batch job** form, select the batch that you created in steps 4 and 5, and then click **Functions** \> **Change status**.

14. Select **Waiting**.

## 4\. Set up a number sequence for positive pay files

Each positive pay file must have a unique number. Use the **Number sequences** form to create a number sequence for positive pay files.

To set up a number sequence for positive pay files, follow these steps:

1.  Open a Microsoft Dynamics AX workspace and switch to the legal entity for which to set up positive pay.

2.  Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**.

3.  Create a number sequence to use for positive pay. For information about how to create a number sequence, see [Set up number sequences](set-up-number-sequences.md).

4.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

5.  Click the **Number sequences** area.

6.  For the **Positive pay number** reference, select a number sequence.

## 5\. Assign a positive pay format to bank accounts

For each bank account that you want to generate positive pay information for, you must assign the positive pay format that was specified in the previous procedure.

To assign the positive pay format to bank accounts, follow these steps:

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Double-click a bank account.

3.  On the **Action Pane**, click **Edit**.

4.  On the **General** FastTab, in the **Positive pay format** field, select the positive pay format that was previously created for this bank.

5.  In the **Positive pay start date** field, enter the first date to generate positive pay files. It is important to enter a date here because without the date, the first positive pay file that you generate includes all checks that were ever created for this bank account.

6.  Repeat steps 2 through 5 for the remaining bank accounts to generate positive pay files for.

## 6\. Set up user security for positive pay

Positive pay files can contain sensitive information about payees and check amounts. It is important that only authorized users have access to generate and view this information in Microsoft Dynamics AX.

To set user security for positive pay, follow these steps:

1.  Identify the users who perform tasks that are related to positive pay files, and the privileges that are required for those tasks. Use the following table to help you decide.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Task</p></th>
    <th><p>Privilege</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Generate positive pay files from the <strong>Bank accounts</strong> list page or the <strong>Bank accounts</strong> form</p></td>
    <td><p><strong>Maintain bank positive pay information</strong> (BankPositivePayProcess)</p>
    <p><strong>Bank positive pay service find operation</strong> (BankPositivePayServiceFind)</p></td>
    </tr>
    <tr class="even">
    <td><p>Generate positive pay files for multiple legal entities and bank accounts from the <strong>Generate a positive pay file</strong> form</p></td>
    <td><p><strong>Maintain bank positive pay information</strong> (BankPositivePayProcess)</p>
    <p><strong>Bank positive pay service find operation</strong> (BankPositivePayServiceFind)</p></td>
    </tr>
    <tr class="odd">
    <td><p>View positive pay files in the <strong>Positive pay file summary</strong> form</p></td>
    <td><p><strong>View bank positive pay information for multiple legal entities</strong> (BankPositivePayView)</p></td>
    </tr>
    <tr class="even">
    <td><p>Confirm a bank positive pay file in the <strong>Positive pay file summary</strong> form</p></td>
    <td><p><strong>Confirm positive payment file</strong> (BankPositivePayConfirm)</p></td>
    </tr>
    <tr class="odd">
    <td><p>Recall a bank positive pay file in the <strong>Positive pay file summary</strong> form</p></td>
    <td><p><strong>Recall positive pay file</strong> (BankPositivePayRecall)</p></td>
    </tr>
    <tr class="even">
    <td><p>Generate positive pay files for the payroll bank account</p></td>
    <td><p><strong>Maintain payroll positive pay information</strong> (PayrollPositivePayProcess)</p></td>
    </tr>
    <tr class="odd">
    <td><p>View payroll positive pay files in the <strong>Payroll positive pay file summary</strong> form</p></td>
    <td><p><strong>View payroll positive pay information</strong> (PayrollPositivePayView)</p>
    <p><strong>Maintain payroll positive pay information</strong> (PayrollPositivePayProcess)</p></td>
    </tr>
    <tr class="even">
    <td><p>Confirm a payroll bank positive pay file in the <strong>Payroll positive pay file summary</strong> form</p></td>
    <td><p><strong>Maintain payroll positive pay information</strong> (PayrollPositivePayProcess)</p></td>
    </tr>
    <tr class="odd">
    <td><p>Recall a payroll positive pay file from the <strong>Payroll positive pay file summary</strong> form</p></td>
    <td><p><strong>Maintain payroll positive pay information</strong> (PayrollPositivePayProcess)</p></td>
    </tr>
    </tbody>
    </table>


2.  Assign the users to roles that contain the privileges that are specified in the previous step. For more information, see Set up user security.

## Related tasks

[Generate and print vendor checks](generate-and-print-vendor-checks.md)

[Issue worker payments](issue-worker-payments.md)

[Create a positive pay file for multiple legal entities and bank accounts](create-a-positive-pay-file-for-multiple-legal-entities-and-bank-accounts.md)

[Set up a review process for reversals and cancellations](set-up-a-review-process-for-reversals-and-cancellations.md)

[Void unposted checks](void-unposted-checks.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and privilege</strong></p></td>
<td><p>To perform this task, you must be a member of the <strong>-SYSADMIN-</strong> security role.</p>
<p>To assign positive pay formats to bank accounts, you must be a member of a security role that includes the following duty:</p>
<ul>
<li><p><strong>Maintain bank accounts master</strong> (BankBankAccountsMaintain)</p></li>
</ul>
<p>To set up a number sequence for positive pay, you must be a member of a security role that includes the following privilege and duty:</p>
<ul>
<li><p><strong>Maintain bank parameters</strong> (BankParametersMaintain)</p></li>
<li><p><strong>Inquire about translation setup and sessions</strong> (RTSLTranslationInquire)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


