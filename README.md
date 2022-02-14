# ApplicationLoadBalancer-using-terraform

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)]()

An Application Load Balancer functions at the application layer, the seventh layer of the Open Systems Interconnection (OSI) model. After the load balancer receives a request, it evaluates the listener rules in priority order to determine which rule to apply, and then selects a target from the target group for the rule action. You can configure listener rules to route requests to different target groups based on the content of the application traffic. Routing is performed independently for each target group, even when a target is registered with multiple target groups. You can configure the routing algorithm used at the target group level. The default routing algorithm is round robin; alternatively, you can specify the least outstanding requests routing algorithm.

## Description:

The Application Load Balancer is a feature of Elastic Load Balancing that allows a developer to configure and route incoming end-user traffic to applications based in the AWS public cloud. Application Load Balancer enables content-based routing and allows requests to be routed to different applications behind a single load balance. While the Classic Load Balancer doesn't do that, a single ELB can host single application. Application Load Balancer works in Layer 7 of the OSI reference model for how applications communicate over a network.
