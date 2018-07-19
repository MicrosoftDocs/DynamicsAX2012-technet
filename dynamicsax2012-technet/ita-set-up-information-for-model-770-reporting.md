---
title: (ITA) Set up information for Model 770 reporting
TOCTitle: (ITA) Set up information for Model 770 reporting
ms:assetid: 7787a3d9-06c8-46ce-a5c2-f08e79dcbc2d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh856770(v=AX.60)
ms:contentKeyID: 45688018
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Italy
- Modello 770
audience: Application User
ms.search.region: Italy
---

# (ITA) Set up information for Model 770 reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Model 770 report is an annual report that provides information about the taxes that are withheld by a company when the company pays contractors and self-employed vendors. Companies remit the withheld taxes directly to the government throughout the year. At the end of the year, the company generates and transmits the Model 770 report, which itemizes the payments that were made and the taxes that were withheld, to each vendor. The Model 770 report contains only information about contractors and self-employed vendors for whom taxes were withheld from payments.

Complete the following tasks before you generate a Model 770 report and export it as an ASCII file:

  - Set up a withholding tax code, withholding tax group, withholding tax limit, and withholding tax value. For more information, see [Withholding tax configuration key (LedgerBasicWithholdingTax)](withholding-tax-configuration-key-ledgerbasicwithholdingtax.md), [Withholding tax codes (form)](https://technet.microsoft.com/en-us/library/aa585361\(v=ax.60\)), [Withholding tax groups (form)](https://technet.microsoft.com/en-us/library/aa591973\(v=ax.60\)), [Withholding tax limits (form)](https://technet.microsoft.com/en-us/library/aa592034\(v=ax.60\)), and [Withholding tax values (form)](https://technet.microsoft.com/en-us/library/aa615586\(v=ax.60\)).

  - Set up withholding tax for a vendor. For more information, see [(Global, AUS, ITA) Set up withholding tax for a vendor](global-aus-ita-set-up-withholding-tax-for-a-vendor.md).

  - Pay a vendor invoice and withhold taxes from the payment. For more information, see [Journal voucher - Vendor payment journal (form)](https://technet.microsoft.com/en-us/library/aa599011\(v=ax.60\)) and [About payment types](about-payment-types.md).

  - Set up an Italian sales tax book. For more information, see [(ITA) Italian sales tax books (form)](https://technet.microsoft.com/en-us/library/aa620738\(v=ax.60\)).

## Set up address information for a self-employed vendor or contractor

Use the **Address setup** form to set up the country code, state and region code, and county and municipality codes for a self-employed vendor or contractor to include in a Model 770 report. You must set up address information for all self-employed vendors and contractors for whom you withhold taxes from payments. For more information, see [Address setup (form)](https://technet.microsoft.com/en-us/library/hh209301\(v=ax.60\)).For information about the address codes, see the Italian government’s instructions for the Model 770 report published on the [Italian Revenue Agency](http://www.agenziaentrate.gov.it/wps/wcm/connect/nsilib/nsi/strumenti/modelli/modelli+di+dichiarazione+2010/770_2010+semplificato/) website.

1.  Click **Organization administration** \> **Setup** \> **Addresses** \> **Address setup**.

2.  Click the **Country/region** link, and then press CTRL+N to create a new country code.

3.  In the **Country/region** field, enter the two-letter International Organization for Standardization (ISO) country code for Italy.

4.  Click the **State/province** link, and then in the **State** and **IT state code** fields, enter the identification code of the state and two-digit IT region code for the self- employed vendor or contractor.
    

    > [!NOTE]
    > <P>Use the numeric state code, not the state acronym.</P>



5.  Click the **County** link, and then in the **Italian county code** field, enter the two-letter ISO county code for the vendor or contractor.

6.  Click the **City** link, and then in the **IT municipality code** field, enter the four-character Italian municipality code for the vendor or contractor. The code consists of a letter and three numbers.

7.  Click the **ZIP/postal codes** link, and then in the **ZIP/postal code** field, enter the Italian postal code.

8.  Close the form.

## Set up the birth county and heir status for a self-employed vendor

Use the **Vendors** form to set up information about a self-employed vendor’s birth county and status as an heir to the company. For more information, see [Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\)).You can use the tax exempt number defined on the **Invoice and delivery** FastTab in the **Vendors** form to determine if the vendor is an individual or company. If the vendor has a tax exempt number, the vendor is considered a company; otherwise, the vendor is considered an individual. You can set up the birth county and heir status only for vendors who are considered individuals. The birth county, heir status, and fiscal code of the vendor are included in the Model 770 report.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a self-employed vendor, and then click **Edit** to open **Vendors** form.

3.  Click the **Invoice and delivery** FastTab, and then in the **Fiscal code** field, enter the fiscal code of the vendor.
    

    > [!NOTE]
    > <P>For self-employed vendors who are not required to pay VAT, enter the personal fiscal code of the individual. If the vendor is required to pay VAT, enter the VAT registration number (partita IVA) provided by the Italian tax authority as the fiscal code of the vendor.</P>



4.  Click the **Purchasing demographics** FastTab, and then in the **Birth county** field, select the county where the vendor was born.

5.  Select the **Heir** check box to identify the vendor as an heir to the company.

6.  Close the form.

## Set up a fiscal code for the legal entity

Use the **Legal entities** form to set up the fiscal code for your legal entity. You can use the fiscal code for tax declarations. The fiscal code is included in the Model 770 report to allow the Italian government to identify your legal entity. For more information, see [Legal entities (form)](https://technet.microsoft.com/en-us/library/hh242860\(v=ax.60\)).

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Click the **Statutory reporting** FastTab, and then in the **Fiscal code** field, enter the fiscal code of the legal entity.

3.  Close the form.

## Set up a number sequence for the Model 770 report

Use the **General ledger parameters** form to set up a number sequence for the Model 770 report.For more information,see[General ledger parameters (form)](https://technet.microsoft.com/en-us/library/aa557286\(v=ax.60\))

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click the **Number sequences** link, and then in the **Number sequence code** field, select a number sequence for the **Model ID** reference.

3.  Close the form.

## See also

[(ITA) Create and export the Model 770 report as an ASCII file](ita-create-and-export-the-model-770-report-as-an-ascii-file.md)

  


