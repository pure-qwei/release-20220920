## hmctl snapshot update

Updates a specific Snapshot.

```
hmctl snapshot update [flags]
```

### Options

```
      --authorization string      Access token for authorization header.
      --destroyed                 True if the resource should be destroyed.
  -h, --help                      help for update
  -n, --name string               The name of the Snapshot. (Required)
  -t, --tenant string             The name of the Tenant. (Required)
  -s, --tenant-space string       The name of the Tenant Space. (Required)
      --x-correlation-id string   Add correlation id to header.
      --x-request-id string       Add operation idempotence id to header.
```

### Options inherited from parent commands

```
      --output-format string   Output format (default "pretty-print")
      --profile string         Configuration profile to use
```

### SEE ALSO

* [hmctl snapshot](hmctl_snapshot.md)	 - Perform operations on snapshot resources

###### Auto generated by spf13/cobra on 26-Sep-2022
