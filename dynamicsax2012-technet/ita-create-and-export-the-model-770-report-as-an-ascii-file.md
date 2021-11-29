---
title: (ITA) Create and export the Model 770 report as an ASCII file
TOCTitle: (ITA) Create and export the Model 770 report as an ASCII file
ms:assetid: 933893a6-abeb-42dd-b915-2d212838471e
ms:mtpsurl: https://technet.microsoft.com/library/Hh528493(v=AX.60)
ms:contentKeyID: 37835229
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Italy
- ASCII file
- Modello 770
audience: Application User
ms.search.region: Italy
---

# (ITA) Create and export the Model 770 report as an ASCII file 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Withholding tax - Model 770** form to generate the Model 770 report and export the information to an ASCII file to submit to the tax authorities. The Model 770 report is an annual report that provides information about the taxes that are withheld by a company when the company pays contractors and self-employed vendors. The name of the ASCII file must be \[company fiscal code\] 77S\[YY\].77s, where YY is the last two digits of the filing year.

For more information about completing and filing the Model 770 report, see the [Italian Revenue Agency](http://www.agenziaentrate.gov.it/wps/wcm/connect/nsilib/nsi/strumenti/modelli/modelli+di+dichiarazione+2010/770_2010+semplificato/) website.

1.  **General ledger** \> **Reports** \> **External** \> **Withholding tax - Model 770**

2.  Press CTRL+N to create a new report. The report is numbered according to the number sequence that you set up for the **Modello 770 Export** reference on the **Number sequences** link in the **General ledger parameters** form.

3.  In the **Filing year** field, enter the year for the tax filing. For example, enter 2011 as the filing year for the tax year 2010. The default value is the current calendar year.

4.  Click the **Report information** FastTab, and then in the **ATECOFIN Code** field, enter the company’s ATECOFIN code. This code is defined in the **Italian sales tax books** form.

5.  In the **Declaration type** field, select **Integrative** to compile and submit a new report if you have already submitted a report that requires corrections.

6.  In the **Exceptional event** field, select any exceptional event that your company was subject to during the tax year from the following options:
    
      - **No exceptional events** – There were no exceptional events. This option is displayed by default.
    
      - **Extortion** – The company was extorted and obtained an extension of three years from the Italian government to meet their tax obligations.
    
      - **Abruzzo earthquakes** – The company was affected by the 2009 Abruzzo earthquake.
    
      - **Exceptional circumstances** – The company was subject to various exceptional situations that resulted in the suspension of tax submissions for a period defined by the Italian government.

7.  In the **Status** field, select the operational status of the company from the following options:
    
      - **Normal operation** – The company is operating as usual. This option is displayed by default.
    
      - **In liquidation** – The company is in liquidation.
    
      - **In bankruptcy** – The company is in bankruptcy.
    
      - **Business closed** – The company’s operations are closed.

8.  In the **Situation** field, select the tax period type from the following options:
    
      - **Liquidation tax period** – The report covers the tax period when the company was in liquidation.
    
      - **Tax period after bankruptcy** – The report covers the tax period after the company filed bankruptcy.
    
      - **Tax period when liquidation ended** – The report covers the tax period when the company’s liquidation ended.
    
      - **IRES transformation tax period** – The report covers the tax period specified by the Imposta sul Reddito delle Società (IRES), or corporate income tax, when the company underwent a transformation.
    
      - **Normal tax period** – The report covers the usual tax period. This option is displayed by default.

9.  In the **Editorial comments** field, select the section for which the company must file the withheld tax from the following options:
    
      - **Section I**
    
      - **Section II**
    
      - **Section III**
    
      - **Section IV**
    

    > [!NOTE]
    > <P>The default value is <STRONG>Section II</STRONG>. You can select the section based on the Italian government’s instructions for the Model 770 report published on the <A href="http://www.agenziaentrate.gov.it/wps/wcm/connect/nsilib/nsi/strumenti/modelli/modelli+di+dichiarazione+2010/770_2010+semplificato/">Italian Revenue Agency</A> website.</P>



10. In the **Role** field, select the employee’s role from the following options:
    
      - **Legal representative** – The employee is a managing partner.
    
      - **Administrator of under aged** – The employee is an administrator for minors or people with disabilities.
    
      - **Bankruptcy curator** – The employee is a bankruptcy curator.
    
      - **Commissioned liquidator** – The employee is a liquidation administrator.
    
      - **Controller of sequestered goods** – The employee is an administrator for seized goods.
    
      - **Fiscal representative** – The employee is a tax representative for non-residents.
    
      - **General legatee** – The employee is an heir to the company.
    
      - **Liquidator** – The employee is an administrator for a voluntary liquidation.
    
      - **Extraordinary operator** – The employee is a representative who submits tax returns on behalf of a company that no longer exists because of a merger, acquisition, or other extraordinary transaction.
    
      - **Non-resident** – The employee is a tax representative for non-residents, with limitations as defined under article. 44, paragraph 3, of [D.L. No 331/1993](http://www.agenziaentrate.gov.it/wps/wcm/connect/nsilib/nsi/strumenti/studi+di+settore/normativa+prassi+e+giurisprudenza/leggi%2c+decreti+e+provvedimenti/archivio+leggi+provv+studi+settore/anni+precedenti+1999+-+1993/studi+di+settore+-+prime+norme).
    
      - **Legal guardian** – The employee is a guardian for a minor who is an heir to the company.
    
      - **Sole proprietor liquidator** – The employee is an administrator who is responsible for disposing of company equipment during a voluntary liquidation.
    
      - **Property manager** – The employee is a property manager.
    
      - **Public representative** – The employee is a representative who signs the declarations on behalf of the government.
    
      - **Public liquidator** – The employee is a liquidator who operates on behalf of the government.

11. Click the **Withholding tax transactions** FastTab, and then click **Transfer** to transfer the vendor payment and withholding transactions to the Model 770 report. Verify the transactions with your records and with the **Withholding tax - yearly report**.

12. Click **Validate** to validate the data that you set up for vendors and the company.

13. Click **Export** to open the **Modello 770 Export** form, and then in the **Export directory** field, specify a path to export the Model 770 report as an ASCII file.

14. Select the **Confirm flag** check box to initiate the import process by bypassing the validation logic in the government import tool. You can also select this check box if you are working with a previously submitted report that was rejected but that you consider correct and complete in terms of available information published on the [Italian Revenue Agency](http://www.agenziaentrate.gov.it/wps/wcm/connect/nsilib/nsi/strumenti/modelli/modelli+di+dichiarazione+2010/770_2010+semplificato/) website.

15. Click **OK** to export the Model 770 report in the required ASCII format.

16. Close the form.

You can save and close the report numerous times without actually creating the file. You can also export the file several times, if necessary.

## See also

[(ITA) Withholding tax - Model 770 (form)](https://technet.microsoft.com/library/hh706143\(v=ax.60\))

  


