---
title: bitsadmin listfiles
description: Reference topic for the bitsadmin listfiles command, which lists the files in the specified job.
ms.prod: windows-server
ms.technology: manage-windows-commands
ms.topic: article
ms.assetid: ad0d1eaa-3bd8-45e5-8f72-4da7366f0d59
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---

# bitsadmin listfiles

Lists the files in the specified job.

## Syntax

```
bitsadmin /listfiles <job>
```

### Parameters

| Parameter | Description |
| -------------- | -------------- |
| job | The job's display name or GUID. |

## Examples

To retrieve the list of files for the job named *myDownloadJob*:

```
bitsadmin /listfiles myDownloadJob
```

## Additional References

- [Command-Line Syntax Key](command-line-syntax-key.md)

- [bitsadmin command](bitsadmin.md)
