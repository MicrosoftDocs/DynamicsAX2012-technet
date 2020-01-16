---
title: Retail Benchmark for Microsoft Dynamics AX 2012 R2
TOCTitle: Retail Benchmark for Microsoft Dynamics AX 2012 R2
ms:assetid: b87b9f72-c6fb-4100-b020-501e7688cd7d
ms:mtpsurl: https://technet.microsoft.com/library/Dn715997(v=AX.60)
ms:contentKeyID: 62200222
author: Khairunj
ms.date: 08/18/2014
mtps_version: v=AX.60
---

# Retail Benchmark for Microsoft Dynamics AX 2012 R2 


In 2013, Microsoft conducted a benchmark on Microsoft Dynamics AX 2012 R2 to measure the performance and scalability characteristics of the Microsoft Dynamics AX 2012 R2 retail solution in a simulated retail scenario. The benchmark showcases the ability of Microsoft Dynamics AX 2012 R2 to handle various specialized loads concurrently, without compromising performance and scalability on critical business processes. The benchmark includes many functional scenarios across different client and integration technologies, thereby providing a view of retail back-end scenarios. The following scenarios were executed to complete the benchmark:

The following scenarios were executed to complete the benchmark:

  - Trickle feed of point of sale (POS) transactions from stores

  - End-of-day processing of POS transactions:
    
      - Inventory reservations were made for the imported transactions.
    
      - Imported POS transactions were consolidated and aggregated, and then transferred to statements in a peak load situation.
    
      - Statements were processed and transferred to sales orders, and financial updates were posted.

The scenarios generate load on an instance of Application Object Server (AOS).

With minimal hardware, we were able to complete end-of-day processing for 800,000 POS transactions in approximately four hours.

We have published the following two papers about the Retail benchmark for Microsoft Dynamics AX 2012 R2:

  - [Microsoft Dynamics AX 2012 R2 Retail benchmark for multiple retail workloads detailed results](http://go.microsoft.com/fwlink/?linkid=302114) This paper provides detailed results of the Retail benchmark testing and can be downloaded from CustomerSource and PartnerSource.

  - [Microsoft Dynamics AX 2012 R2 Retail benchmark summary results](http://go.microsoft.com/fwlink/?linkid=302129) This paper provides a summary of the Retail benchmark testing and can be downloaded from CustomerSource and PartnerSource.

For more information about Retail performance, see [Retail Performance for Microsoft Dynamics AX 2012](retail-performance-for-microsoft-dynamics-ax-2012.md).

  


