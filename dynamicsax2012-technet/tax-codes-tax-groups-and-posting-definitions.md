---
title: Tax codes, tax groups, and posting definitions
TOCTitle: Tax codes, tax groups, and posting definitions
ms:assetid: 57b01627-e821-491d-b460-c4225b4dfc68
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527692(v=AX.60)
ms:contentKeyID: 59626226
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- posting definition
- posting definitions
- tax codes
- tax code
- payroll tax code
- payroll taxes
- payroll tax codes
- tax groups
- tax group
- payroll tax group
- payroll tax groups
---

# Tax codes, tax groups, and posting definitions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic answers questions you might have when you work with tax codes and tax groups, and when you use tax groups together with posting definitions. Tax groups let you designate transaction posting definitions for multiple tax codes at the same time. If you use tax groups to do this and you’re not getting the posting results that you want, the questions in this topic can help you resolve the issues.

This topic describes functionality that is available only if the **Payroll - USA** configuration key is selected.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## Can I mass-update tax codes?

Yes, you can update all the tax codes in a tax group at the same time.

The financial information for each tax code is set up separately for each legal entity. If you change the values for one legal entity, the values for other legal entities aren’t affected.

When you update a tax code by using the mass-update functionality, the changes are effective immediately. To make date-effective changes to a tax code, use the **Maintain versions** button in the **Tax codes** form.

1.  Click **Payroll** \> **Setup** \> **Taxes** \> **Tax groups**.

2.  Select a tax group, and then click **Mass update**.

3.  Select the legal entity to update the tax group for.

4.  Select one or more of the following fields to update:
    
      - **Vendor**
    
      - **Project category**
    
      - **Default financial dimensions**
    
      - **Main account**

5.  Enter the new values for the selected fields.
    

    > [!WARNING]
    > <P>If you select a field and you don’t enter a value, the field is cleared on all the tax codes in the tax group.</P>



6.  Review the list of affected tax codes to make sure that you want to change every tax code in the list.

7.  Click **Update**.

## Can I mass-create tax groups?

Yes. When you set up Payroll, you automatically create a set of system-defined tax groups the first time that you click the **Update tax data** link on the **Payroll** area page. Each system-defined tax group contains tax codes of a particular type. For example, all tax codes for school districts are included in the SCHL tax group, and all tax codes for state income tax are in the SIT tax group. These tax groups are updated every time that you run the **Update tax data** process.

You can manually create additional tax groups. For more information, see [Tax information tasks](tax-information-tasks.md).

## Why do some tax codes not post according to the posting definition that is associated with their tax group?

There are two reasons this might occur:

  - The **Employer tax** check box for the tax code in the **Tax codes** form is incorrect for the line type in the **Transaction posting definitions** form.
    
    If some tax codes in a tax group have the correct employer tax setting for the line type and some don’t, the tax codes that have the correct setting use the posting definition for the tax group. The other tax codes use the posting definition that is specified for the **All** code for their line type. The correct relationships of line types and employer tax settings are shown in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Line type</p></th>
    <th><p>Required setting for the <strong>Employer tax</strong> check box</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Tax - contribution</strong></p></td>
    <td><p>Selected</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tax - deduction</strong></p></td>
    <td><p>Cleared</p></td>
    </tr>
    </tbody>
    </table>


  - The tax code is entered on a line in the **Transaction posting definitions** form that uses the **Table** code. Table lines take precedence over group lines. The following table shows what you can enter in **Payroll code** field based on what is in the **Code** field, and what occurs from the combination of code and payroll code.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p><strong>Code</strong></p></th>
    <th><p><strong>Payroll code</strong></p></th>
    <th><p>Result</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Table</strong></p></td>
    <td><p>A tax code</p></td>
    <td><p>The tax code uses the specified transaction posting definition, even if the tax code is in a tax group that uses a different posting definition.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Group</strong></p></td>
    <td><p>A tax group</p></td>
    <td><p>All tax codes in the tax group use the specified transaction posting definition, except any tax codes that are on a <strong>Table</strong> line.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>All</strong></p></td>
    <td><p>[Blank]</p></td>
    <td><p>Any tax code that does not post according to a <strong>Table</strong> line or a <strong>Group</strong> line uses the transaction posting definition that is specified for <strong>All</strong>.</p></td>
    </tr>
    </tbody>
    </table>


## Why can’t I delete a tax group?

You can’t delete a tax group that is system-defined or that is enabled for posting definitions.

## Why can’t I remove a tax code from a tax group?

You can’t remove a tax code from a system-defined tax group.

## Why can’t I select Group in the Code field? The only options I see are Table and All.

In the **Transaction posting definitions** form, the **Group** option is available only for line types of **Tax - contribution** and **Tax - deduction**.

## Can I delete a tax code from a tax group that is enabled for posting definitions?

Yes, you can. In the **Tax codes** form, clear the **Enable posting definitions** check box, delete the tax code, and then select the check box again.

## Can I disable posting definitions for a tax group?

Yes, but you can’t disable posting definitions for a tax group that is used in a transaction posting definition. If you open the **Transaction posting definitions** form and delete the line that uses the tax group, you can clear the **Enable posting definitions** check box in the **Tax codes** form.

## Why can a tax code belong to only one tax group that is enabled for posting definitions?

A tax code can belong to only one tax group that is enabled for posting definitions to make sure that the tax is posted to the correct account.

If a tax code were included in two groups, the system would use the posting definition for whichever group was processed first. For example, you could include the Colorado state income tax in both the state income tax group and the Colorado tax group. If both groups were enabled for posting definitions, the system would not consistently use the same posting definition for the Colorado state income tax. Sometimes, the tax might be posted by using the posting definition for the state income tax group. Other times, the tax might by posted by using the posting definition for the Colorado tax group. You would never know which posting definition was used.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

