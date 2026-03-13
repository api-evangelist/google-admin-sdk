# Google Admin SDK

The Google Admin SDK provides a collection of RESTful APIs for managing Google Workspace organizations at scale. It includes the Directory API for managing users, groups, devices, and organizational units; the Reports API for auditing activity and usage; and the Data Transfer API for migrating data between users. These APIs enable programmatic integration with enterprise IT infrastructure.

## Base URL

```
https://admin.googleapis.com
```

## Resources

The Admin SDK Directory API provides the following resources:

- **Users** - Create, read, update, delete, and manage user accounts
- **Groups** - Manage groups and group memberships
- **Members** - Add, remove, and list group members
- **Organizational Units** - Manage the organizational hierarchy
- **Chrome OS Devices** - Manage Chrome OS device inventory
- **Mobile Devices** - Manage mobile device inventory
- **Roles** - Define and assign administrative roles
- **Domains** - Manage domain settings
- **Customers** - Manage customer account information
- **Tokens** - Manage OAuth tokens
- **Schemas** - Define custom user attribute schemas

## Artifacts

| Artifact | Path |
|----------|------|
| APIs.yml | [apis.yml](apis.yml) |
| OpenAPI 3.1.0 | [openapi/openapi.yml](openapi/openapi.yml) |
| JSON Schema (Draft 2020-12) | [json-schema/json-schema.yml](json-schema/json-schema.yml) |
| JSON-LD Context | [json-ld/json-ld.jsonld](json-ld/json-ld.jsonld) |

## Documentation

- [Admin SDK Overview](https://developers.google.com/workspace/admin/overview)
- [Directory API Reference](https://developers.google.com/workspace/admin/directory/reference/rest)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
