---
title: "-DYNAMICBASE | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: ["cpp-tools"]
ms.topic: "reference"
f1_keywords: ["/dynamicbase"]
dev_langs: ["C++"]
helpviewer_keywords: ["-DYNAMICBASE editbin option", "DYNAMICBASE editbin option", "/DYNAMICBASE editbin option"]
ms.assetid: edb3df90-7b07-42fb-a94a-f5a4c1d325d6
author: "corob-msft"
ms.author: "corob"
ms.workload: ["cplusplus"]
---
# /DYNAMICBASE
Specifies whether an executable image can be randomly rebased at load time by using address space layout randomization (ASLR).  
  
## Syntax  
  
```  
  
/DYNAMICBASE[:NO]  
```  
  
## Remarks  
 By default, the linker sets the **/DYNAMICBASE** option.  
  
 This option modifies the header of an executable image to indicate whether the loader can randomly rebase the image at load time.  
  
 ASLR is supported on Windows Vista, Windows Server 2008, Windows 7, Windows 8, and Windows Server 2012.  
  
## See Also  
 [EDITBIN Options](../../build/reference/editbin-options.md)   
 [Windows ISV Software Security Defenses](http://msdn.microsoft.com/library/bb430720.aspx)