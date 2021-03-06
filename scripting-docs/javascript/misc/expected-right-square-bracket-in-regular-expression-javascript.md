---
title: "Expected &#39;]&#39; in regular expression (JavaScript) | Microsoft Docs"
ms.custom: ""
ms.date: "01/18/2017"
ms.prod: "windows-client-threshold"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "javascript"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "VS.WebClient.Help.SCRIPT5019"
dev_langs: 
  - "JavaScript"
  - "DHTML"
ms.assetid: 1ca2079a-44dd-479f-a1e3-e04a14d0739e
caps.latest.revision: 7
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
---
# Expected &#39;]&#39; in regular expression (JavaScript)
You attempted to create a character class for a regular expression match, but did not include the right bracket. Individual literal character combinations can be assembled into character classes by placing them within brackets. A character class matches any one character it contains. For example, /[abc]/ matches any one of the letters "a", "b", or "c".  
  
### To correct this error  
  
-   Add the right bracket to the regular expression.  
  
    > [!NOTE]
    >  If you want to match a single bracket, escape it with a backslash - \\[ - so it is not interpreted as a special character by [!INCLUDE[javascript](../../javascript/includes/javascript-md.md)].  
  
## See Also  
 [Regular Expression Object](../../javascript/reference/regular-expression-object-javascript.md)   
 [Regular Expression Syntax (JavaScript)](http://msdn.microsoft.com/en-us/ab0766e1-7037-45ed-aa23-706f58358c0e)