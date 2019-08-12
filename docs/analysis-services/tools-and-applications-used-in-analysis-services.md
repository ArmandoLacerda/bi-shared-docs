---
title: "Tools and applications used in Analysis Services | Microsoft Docs"
ms.date: 08/10/2019
ms.prod: sql
ms.technology: analysis-services
ms.custom:
ms.topic: conceptual
ms.author: owend
ms.reviewer: owend
author: minewiskan
manager: kfile
---
# Tools and applications used in Analysis Services
[!INCLUDE[ssas-appliesto-sqlas-aas](../includes/ssas-appliesto-sqlas-aas.md)]

  Find the tools and applications you'll need for building Analysis Services models and managing deployed databases.  
  
## Analysis Services Model Designers  
 Models are authored by using project templates in SQL Server Data Tools (SSDT), a Visual Studio shell. Project templates provide  model designers for creating the data model objects that comprise an Analysis Services solution. SSDT is a free web download updated monthly.

 **[Download SQL Server Data Tools (SSDT)](https://docs.microsoft.com/sql/ssdt/download-sql-server-data-tools-ssdt)** 
  
 Models have a compatibility level setting that determines feature availability and which release of Analysis Services run the model.  Whether you can specify a given compatibility level is determined in-part by the model designer.  
  
 Tabular models using the latest functionality, such as BIM files in tabular JSON format and bi-directional cross filtering, must be created or upgraded at compatibility level 1200 or higher.  
  
 If you require a lower compatibility level, perhaps because you want to deploy a model on an earlier version of Analysis Services, you can still use the model designer in SSDT. Newer versions of the tool support creating any model type (tabular or multidimensional), at any compatibility level.   

## Administrative tools  
  
 SQL Server Management Studio (SSMS) is the primary administration tool for all SQL Server features, including Analysis Services. SSMS is a free web download updated monthly. 
  
**[Download SQL Server Management Studio](https://docs.microsoft.com/sql/ssms/download-sql-server-management-studio-ssms)** 
  
 SSMS includes extended events (xEvents), providing a lightweight alternative to SQL Server Profiler traces used for monitoring activity and diagnosing problems on SQL Server 2016 and Azure Analysis Services servers. See [Monitor Analysis Services with SQL Server Extended Events](../analysis-services/instances/monitor-analysis-services-with-sql-server-extended-events.md) to learn more.  
  
### SQL Server Profiler  
 Although it's officially deprecated in favor of xEvents, SQL Server Profiler provides a familiar approach for monitoring connections, MDX query execution, and other server operations. SQL Server Profiler is installed by default. You can find it with SQL Server applications on Apps in Windows.  
  
### PowerShell  
 You can use PowerShell commands to perform many administrative tasks. See [PowerShell reference](../analysis-services/powershell/analysis-services-powershell-reference.md) for more information.
 
  
