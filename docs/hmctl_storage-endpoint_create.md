## hmctl storage-endpoint create

Creates a Storage Endpoint.

```
hmctl storage-endpoint create [flags]
```

### Examples

```
hmctl storage-endpoint create -r region1 -z az1 --name storage-endpoint-az1 --endpoint-type iscsi -- --address 10.9.25.101/23 --gateway 10.9.25.1 --network-interface-groups group-0 -- --address 10.9.26.101/23 --gateway 10.9.26.1 --network-interface-groups group-1
```

### Options

```
      --authorization string       Access token for authorization header.
  -z, --availability-zone string   The name of the Availability Zone. (Required)
      --display-name string        The display name of the resource.
      --endpoint-type string       The type of this Storage Endpoint. (Required)
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

* [hmctl storage-endpoint](hmctl_storage-endpoint.md)	 - Perform operations on storage-endpoint resources

###### Auto generated by spf13/cobra on 26-Sep-2022
