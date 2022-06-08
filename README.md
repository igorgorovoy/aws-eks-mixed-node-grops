# EKS with mixed managed node groups uses  Graviton2 (arm) and x86_64 arch Instances.
Provision Terraform

This repository provides example Terraform configuration for building an EKS cluster with a Managed Node Group that uses Graviton2 instances (ondemand),
MNG (spot) uses Graviton2 and MNG (spot) uses x86_64 instances.

Graviton instances are generally cheaper than the equivalent x86-based instances .

## Pre-Requisites

To run this example you must have:

- An AWS account (note this example will build resources that will incur charges)
- The machine on which you run it must be logged in to AWS (for example via `aws configure`)
- Terraform 1.0.X installed

## Usage

Clone this repository and run `terraform apply` from the directory containing the code. All variables are optional.

Tear it down with `terraform destroy`.
