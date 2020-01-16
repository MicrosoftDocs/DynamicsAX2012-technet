---
title: (IND) Tax thresholds and tax concession certificates
TOCTitle: (IND) Tax thresholds and tax concession certificates
ms:assetid: 7264e8f3-69ce-420e-aa4d-936aa1f4527d
ms:mtpsurl: https://technet.microsoft.com/library/Dn527715(v=AX.60)
ms:contentKeyID: 59626290
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- India
- concession certificate
- concession certificates
- tax thresholds
- threshold hierarchies
- threshold
- threshold hierarchy
- thresholds
- threshold limits
- threshold value
- threshold values
- threshold limit
- Tax threshold
audience: Application User
ms.search.region: India
---

# (IND) Tax thresholds and tax concession certificates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up and apply threshold limits to calculate direct taxes on customer and vendor transactions. Perform the following tasks to set up and use threshold limits:

1.  Set up threshold limits by creating threshold definitions, and then design threshold segments to set up a threshold hierarchy.

2.  Assign thresholds to a withholding tax code, and set up tax values to apply to the final level of each threshold segment in the threshold hierarchy.

3.  If a customer or a vendor has a concession certificate, set up the details of the tax concession certificate for the customer or vendor.

4.  Set up a withholding tax group that contains the withholding tax code to which you assigned the threshold and the threshold values.

5.  Create and post transactions that use the withholding tax group for the withholding tax code to which you assigned the threshold and threshold values. Microsoft Dynamics AX calculates direct taxes on transactions based on the threshold segments that you set up in the withholding tax codes and withholding tax groups that apply to the transactions.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## What are the different types of threshold limits in Microsoft Dynamics AX?

You can apply the following types of threshold limits on transactions in Microsoft Dynamics AX:

  - **Cumulative threshold** – The maximum limit of a cumulative transaction value, beyond which direct tax on the transaction value is applied.
    
    For example, you set up a cumulative threshold limit of 100,000, and a tax percentage of 10 percent for vendor account 1001. You create three transactions for the vendor that have values of 35,000, 55,000, and 60,000. The total value for all transactions for vendor account 1001 is 150,000 (which exceeds the threshold limit of 100,000). Direct taxes of 10 percent are calculated and applied on the total value for all transactions.
    
    Total taxable amount = 150,000
    
    Tax amount = 15,000

  - **Transaction threshold** – The maximum limit of an individual transaction value, beyond which direct tax on the transaction value is applied.
    
    For example, you set up a transaction threshold limit of 30,000, and a tax percentage of 10 percent for vendor account 1001. You create three transactions for the vendor that have values of 25,000, 35,000, and 15,000. The transaction value 35,000 exceeds the threshold limit of 30,000. Direct taxes of 10 percent are calculated and applied only on the transaction that exceeds the transaction threshold limit.
    
    Total taxable amount = 35,000
    
    Tax amount = 3,500

  - **Transaction line threshold** – The maximum limit of a transaction line value, beyond which direct tax on the transaction line value is applied.
    
    For example, you set up a transaction threshold limit of 10,000, and a tax percentage of 10 percent for vendor account 1001. You create a transaction for the vendor that has transaction line values of 5,000, 25,000, and 15,000. The transaction line values 25,000 and 15,000 exceed the threshold limit of 10,000. Direct taxes of 10 percent are calculated and applied only on the transaction lines that exceed the transaction threshold limit.
    
    Total taxable amount = 40,000
    
    Tax amount = 4,000

If Microsoft Dynamics AX previously calculated direct taxes by using thresholds for a transaction line or a transaction, thresholds and direct taxes are not applied to that transaction line or transaction again. The transaction line or transaction is excluded from threshold and direct tax calculations.

## Where can I use the threshold limits in Microsoft Dynamics AX?

You can use threshold limits to apply taxes, tax concessions, or tax exemptions to customer and vendor transactions in Microsoft Dynamics AX.

## What are the methods that I can use to define the threshold hierarchy structure?

You can design a hierarchy structure for a threshold in the following ways:

  - **Single threshold hierarchy** – This structure contains a single threshold segment. For example, you can set up a threshold by specifying the minimum value of 20,000, and then set up the direct tax percentage of 10 percent when you assign the threshold to an entity. Microsoft Dynamics AX calculates 10 percent direct tax on any transaction that exceeds a value of 20,000.

  - **Progressive threshold hierarchy** – This structure contains multiple threshold segments. You can specify multiple segments in a single level or in multiple levels. You can specify tax rates for each segment when you assign the threshold to an entity. For example, you can create a threshold hierarchy structure with the following segments.
    
    <table>
    <colgroup>
    <col style="width: 25%" />
    <col style="width: 25%" />
    <col style="width: 25%" />
    <col style="width: 25%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Segment</p></th>
    <th><p>Minimum value</p></th>
    <th><p>Maximum value</p></th>
    <th><p>Tax rate</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Segment one</p></td>
    <td><p>0</p></td>
    <td><p>1,00,000</p></td>
    <td><p>5 percent</p></td>
    </tr>
    <tr class="even">
    <td><p>Segment two</p></td>
    <td><p>1,00,000</p></td>
    <td><p>5,00,000</p></td>
    <td><p>10 percent</p></td>
    </tr>
    <tr class="odd">
    <td><p>Segment three</p></td>
    <td><p>5,00,000</p></td>
    <td><p>-</p></td>
    <td><p>15 percent</p></td>
    </tr>
    </tbody>
    </table>


## When do I assign the tax rates to the hierarchy segments of a threshold?

You can specify tax rates that apply to the final levels of the various hierarchy segments of the threshold in the **Threshold designer** form, after you set up a withholding tax code to use the threshold in the **Withholding tax codes** form and then set up an entity to use a threshold in the **Threshold references** form.

## Which PAN status should I select when I specify threshold values for a customer?

If the threshold applies to a customer, a customer group, or all customers, you must select **Not applicable** in the **PAN Status** field in the **Threshold designer** form for each threshold value that you specify.

## Can I set up a concession certificate for a customer or a vendor?

If a customer or a vendor has a concession certificate, you can set up a concession certificate for the customer or vendor in Microsoft Dynamics AX. For more information, see “If required: Set up a tax concession certificate for a customer or vendor” section in the [(IND) Set up thresholds and concession certificates for tax calculations](ind-set-up-thresholds-and-concession-certificates-for-tax-calculations.md) topic.

## When I create a withholding tax code that uses a threshold, what should I select in the Value field in the Withholding tax values form?

When you create a withholding tax code that uses a threshold, leave the **Value** field in the **Withholding tax values** form blank, because you specify the tax values for the final levels of each threshold segment in the **Threshold designer** form.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(IND) Set up threshold limits](ind-set-up-threshold-limits.md)

[(IND) Withholding tax values (modified form)](https://technet.microsoft.com/library/jj710990\(v=ax.60\))

  


