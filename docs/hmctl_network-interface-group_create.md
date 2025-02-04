## hmctl network-interface-group create

Creates a Network Interface Group.

```
hmctl network-interface-group create [flags]
```

### Options

```
      --authorization string       Access token for authorization header.
  -z, --availability-zone string   The name of the Availability Zone. (Required)
      --display-name string        The display name of the resource.
      --eth-gateway string         The IPv4 or IPv6 address of the gateway for this resource.
      --eth-mtu int32              The maximum message transfer unit size for this resource in bytes.
      --eth-prefix string          The IPv4 or IPv6 prefix for this resource.
      --group-type string          The type of this Network Interface Group. (Required)
  -h, --help                       help for create
      --name string                The name of the resource, supplied by the user at creation, and used in the URI path of a resource. (Required)
  -r, --region string              The name of the Region. (Required)
      --x-correlation-id string    Add correlation id to header.
      --x-request-id string        Add operation idempotence id to header.
```

### Options inherited from parent commands

```
      --output-format string   Output format (default "pretty-print")
      --profile string         Configuration profile to use
```

### SEE ALSO

* [hmctl network-interface-group](hmctl_network-interface-group.md)	 - Perform operations on network-interface-group resources.

###### Auto generated by spf13/cobra on 26-Sep-2022
