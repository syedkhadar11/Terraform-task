## Task Details :
We need to use terraform to do this. Create a module called private hosted zone, which accepts a input domain name.

1. Create a first VPC. (only vpc, no need of subnets, RT, NATGW, IGW)

2. Create a secondary VPC (only vpc, no need of subnets, RT, NATGW, IGW)

3. Create Private hosted zone for VPC1. (use input hosted zone)

4. Associate Private hosted zone with VPC2.

5. Delete VPC1 after private hosted zone is connected with VPC2. (This may require customization)
