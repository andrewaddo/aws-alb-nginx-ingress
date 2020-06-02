# AWS Application Load Balancer - NGINX ingress controller

## Other options

1. ALB + ALB ingress controller
   * ALB does not support URL rewrite (as of 2020 Jun 2)
1. NLB + NGINX ingress controller
   * NLB (for EKS) does not support TLS termination
   