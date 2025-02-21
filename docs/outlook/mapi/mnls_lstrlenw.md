---
title: "MNLS_lstrlenW"
description: "MNLS_lstrlenW determines the length of the specified Unicode string, excluding the terminating null character."
manager: soliver
ms.date: 11/16/2014
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
ms.assetid: d342a956-1164-4c9c-b0bb-7a0b72dc97fc
---

# MNLS_lstrlenW

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Determines the length of the specified Unicode string, excluding the terminating null character.
  
> [!TIP]
> Consider using [StringCchLength](https://msdn.microsoft.com/library/ms647539%28VS.85%29.aspx) instead. 
  
```cpp
int MNLS_lstrlen(
  LPCWSTR lpsz);
```

## Parameters

 _lpsz_
  
> [in] The null-terminated Unicode string to be checked.
    
## Return value

The function returns an integer with the length of the string. It is a count of characters in the string, excluding the terminating null character. If  _lpsz_ is NULL, the function returns zero. 
  
## Remarks

This function wraps the **lstrlen** function. For more information, see [lstrlen](https://msdn.microsoft.com/library/ms647492%28VS.85%29.aspx).
  
## See also



[lstrlen](https://msdn.microsoft.com/library/ms647492%28VS.85%29.aspx)
  
[StringCchLength](https://msdn.microsoft.com/library/ms647539%28VS.85%29.aspx)

