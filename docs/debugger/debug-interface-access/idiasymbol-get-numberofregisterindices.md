---
title: "IDiaSymbol::get_numberOfRegisterIndices | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
ms.assetid: 1ec8b8ea-e423-4327-8dc0-a390e6e3ffb0
caps.latest.revision: 3
author: "mikejo5000"
ms.author: "mikejo"
manager: ghogen
---
# IDiaSymbol::get_numberOfRegisterIndices
Retrieves the number of register indices.  
  
## Syntax  
  
```C++  
HRESULT get_numberOfRegisterIndices(   
   DWORD* pRetVal);  
```  
  
#### Parameters  
 `pRetVal`  
 [out] A pointer to a `DWORD` that holds the number of register indices.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns `S_FALSE` or an error code.  
  
## See Also  
 [IDiaSymbol](../../debugger/debug-interface-access/idiasymbol.md)