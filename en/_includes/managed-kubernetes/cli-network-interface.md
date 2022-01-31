* `security-group-ids`: IDs of [Security groups](../../managed-kubernetes/operations/security-groups.md).
* `subnets`: Names of subnets that will host the nodes.
* `ipv4-address`: Method of assigning an IPv4 address.
* `ipv6-address`: Method of assigning an IPv6 address.

`ipv4-address` and `ipv6-address` determine the method of assigning an IP address:
* `auto`: Only the internal IP address will be assigned to the node.
* `nat`: Public and internal IP addresses will be assigned to the node.