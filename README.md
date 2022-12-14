# Azure Virtual Network - Terraform Module

This module can be used to provision Virtual Networks in Azure.

## Usage

The module can be provided with a single variable which defines the values for the virtual network itself, as well as the hierarchy of resources that it would typically contain.

This input variable should specify a list of one or more subnets, which can in turn optionally specify lists of Network Security Groups or Route Tables that should be created and associated with the subnets. Alternatively, the Ids of any pre-existing NSGs or Route Tables can be provided to associate these with any of the subnets.

Usage examples are provided in the examples folder.