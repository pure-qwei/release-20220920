## hmctl host-access-policy create

Creates a Host Access Policy

```
hmctl host-access-policy create [flags]
```

### Options

```
      --authorization string      Access token for authorization header.
      --display-name string       The display name of the resource.
  -h, --help                      help for create
      --iqn string                The iSCSI qualified name (IQN) associated with the host. (Required)
      --name string               The name of the resource, supplied by the user at creation, and used in the URI path of a resource. (Required)
      --personality string        The Personality of the Host machine (Required)
      --x-correlation-id string   Add correlation id to header.
      --x-request-id string       Add operation idempotence id to header.
```

### Options inherited from parent commands

```
      --output-format string   Output format (default "pretty-print")
      --profile string         Configuration profile to use
```

### SEE ALSO

* [hmctl host-access-policy](hmctl_host-access-policy.md)	 - Perform operations on host resources

###### Auto generated by spf13/cobra on 26-Sep-2022
