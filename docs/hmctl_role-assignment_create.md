## hmctl role-assignment create

Assign a Principal (User or API Client) to a Role.

```
hmctl role-assignment create [flags]
```

### Examples

```
hmctl role-assignment create --role "tenant-admin" --scope "/tenants/my-tenant" --api-client "pure1:apikey:ABC123"
hmctl role-assignment create --role "tenant-admin" --scope "/tenants/my-tenant" --principal "12345"
```

### Options

```
      --api-client string         The API Client to assign to the role
      --authorization string      Access token for authorization header.
  -h, --help                      help for create
      --principal string          The unique ID of the Principal (User or API Client) to assign to the Role
      --role string               The name of the Role to assign the Principal to (Required)
      --scope string               The fully-qualified resource path (self_link) to scope the Role Assignment to (Required)
      --x-correlation-id string   Add correlation id to header.
      --x-request-id string       Add operation idempotence id to header.
```

### Options inherited from parent commands

```
      --output-format string   Output format (default "pretty-print")
      --profile string         Configuration profile to use
```

### SEE ALSO

* [hmctl role-assignment](hmctl_role-assignment.md)	 - Perform operations on role assignment resources

###### Auto generated by spf13/cobra on 26-Sep-2022
