---
title: bitsadmin getcustomheaders
description: Windows Commands topic for **bitsadmin getcustomheaders**, which retrieves the custom HTTP headers from the job.
ms.prod: windows-server
ms.technology: manage-windows-commands
ms.topic: article
ms.assetid: 1f0d38d3-e865-4474-81e8-773d65c3d1cc
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017 
---

# bitsadmin getcustomheaders

Retrieves the custom HTTP headers from the job.

## Syntax

```
bitsadmin /getcustomheaders <job>
```

### Parameters

| Parameter | Description |
| -------------- | -------------- |
| job | The job's display name or GUID. |

## <a name=BKMK_examples></a>Examples

The following example gets the custom headers for the job named *myDownloadJob*.

```
C:\>bitsadmin /getcustomheaders myDownloadJob
```

## Additional References

- [Command-Line Syntax Key](command-line-syntax-key.md)