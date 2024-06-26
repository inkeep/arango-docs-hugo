---
title: Oasisctl Delete Audit Log
menuTitle: Delete Audit Log
weight: 2
---
## oasisctl delete auditlog

Delete an auditlog

```
oasisctl delete auditlog [flags]
```

## Options
```
  -i, --auditlog-id string       Identifier of the auditlog to delete.
  -h, --help                     help for auditlog
  -o, --organization-id string   Identifier of the organization
```

## Options Inherited From Parent Commands
```
      --endpoint string   API endpoint of the ArangoDB Oasis (default "api.cloud.arangodb.com")
      --format string     Output format (table|json) (default "table")
      --token string      Token used to authenticate at ArangoDB Oasis
```

## See also
* [oasisctl delete](_index.md)	 - Delete resources
* [oasisctl delete auditlog archive](delete-auditlog-archive.md)	 - Delete an auditlog archive
* [oasisctl delete auditlog destination](delete-auditlog-destination.md)	 - Delete a destination from an auditlog

