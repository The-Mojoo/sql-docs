---
title: "MSSQLSERVER_5245 | Microsoft Docs"
ms.custom: ""
ms.date: "04/04/2017"
ms.prod: "sql-server-2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "database-engine"
ms.tgt_pltfrm: ""
ms.topic: "language-reference"
helpviewer_keywords: 
  - "5245 (Database Engine error)"
ms.assetid: 6005c9ec-ccdd-4def-9eb4-37cdb599ddb3
caps.latest.revision: 17
author: "BYHAM"
ms.author: "rickbyh"
manager: "jhubbard"
---
# MSSQLSERVER_5245
  
## Details  
  
|||  
|-|-|  
|Product Name|SQL Server|  
|Event ID|5245|  
|Event Source|MSSQLSERVER|  
|Component|SQLEngine|  
|Symbolic Name|DBCC4_TABLE_LOCK_TIMEOUT_EXCEEDED|  
|Message Text|Object ID O_ID (object 'NAME'): DBCC could not obtain a lock on this object because the lock request time-out period was exceeded. This object has been skipped and will not be processed.|  
  
## Explanation  
A lock time-out occurred while DBCC was waiting on a table lock for the specified object.  
  
## User Action  
Rerun the DBCC command.  
  
