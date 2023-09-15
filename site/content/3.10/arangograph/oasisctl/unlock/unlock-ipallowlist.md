---
title: Oasisctl Unlock Ipallowlist
menuTitle: Unlock IP Allowlist
weight: 15
description: >-
  Description of the oasisctl unlock ipallowlist command
archetype: default
---
Unlock an IP allowlist, so it can be deleted

## Synopsis

Unlock an IP allowlist, so it can be deleted

```
oasisctl unlock ipallowlist [flags]
```

## Options

```
  -h, --help                     help for ipallowlist
  -i, --ipallowlist-id string    Identifier of the IP allowlist
  -o, --organization-id string   Identifier of the organization
  -p, --project-id string        Identifier of the project
```

## Options inherited from parent commands

```
      --endpoint string   API endpoint of the ArangoDB Oasis (default "api.cloud.arangodb.com")
      --format string     Output format (table|json) (default "table")
      --token string      Token used to authenticate at ArangoDB Oasis
```

## See also

* [oasisctl unlock](_index.md)	 - Unlock resources
