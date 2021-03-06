---
title: bitsadmin cancel
description: Windows Commands topic for **bitsadmin cancel**, which removes the job from the transfer queue and deletes all temporary files associated with the job.
ms.prod: windows-server
ms.technology: manage-windows-commands
ms.topic: article
ms.assetid: 7374b544-6a16-4d3e-872c-dcf4c02ad89d
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---

# bitsadmin cancel

Removes the job from the transfer queue and deletes all temporary files associated with the job.

## Syntax

```
bitsadmin /cancel <job>
```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| job | The job's display name or GUID. |

## <a name=BKMK_examples></a>Examples

The following example removes the *myDownloadJob* job from the transfer queue.

```
C:\>bitsadmin /cancel myDownloadJob
```

## Additional References

- [Command-Line Syntax Key](command-line-syntax-key.md)