<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-azure-linux-virtual-machine/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraspace Azure Linux Virtual Machine

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

This contains example code that creates:

* Azure Network
* Azure Linux Virtual Machine

It uses:

* Terraform Registry Module: [boltops-tools/linux_virtual_machine/azure](https://registry.terraform.io/modules/boltops-tools/linux_virtual_machine/azure)

## Env Vars

You should configure these env vars:

* ARM_CLIENT_ID
* ARM_CLIENT_SECRET
* ARM_SUBSCRIPTION_ID
* ARM_TENANT_ID

As covered in: [Terraspace Azure Getting Started Docs: Configure Azure](https://terraspace.cloud/docs/learn/azure/configure/)

## Deploy

To deploy:

    terraspace up linux_vm

## Video

[![Watch the video](https://uploads-learn.boltops.com/2kp4vp6klpqshupsrl3h8vjpx1gj)](https://learn.boltops.com/courses/terraspace-azure/lessons/terraspace-azure-linux-virtual-machine)

Note: Premium video content requires a subscription.
