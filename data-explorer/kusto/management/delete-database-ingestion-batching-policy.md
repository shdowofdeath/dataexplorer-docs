---
title: .delete database policy ingestionbatching command
description: Learn how to use the `.delete database policy ingestionbatching` command to delete the database ingestion batching policy.
ms.reviewer: yonil
ms.topic: reference
ms.date: 06/13/2023
---
# .delete database policy ingestionbatching command

Use this command to remove the database [ingestion batching policy](batchingpolicy.md) that defines data aggregation for batching.

## Permissions

You must have at least [Database Admin](access-control/role-based-access-control.md) permissions to run this command.

## Syntax

`.delete` `database` *DatabaseName* `policy` `ingestionbatching`

## Parameters

|Name|Type|Required|Description|
|--|--|--|--|
|*DatabaseName*|string|&check;|The name of the database.|

## Example

The following command deletes the batching policy on a database.

```kusto
.delete database MyDatabase policy ingestionbatching
```

## See also

* [delete table batching policy](delete-table-ingestion-batching-policy.md)
