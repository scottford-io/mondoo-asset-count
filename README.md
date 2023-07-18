# Mondoo Asset Inventory Count

This repo contains a Mondoo cnquery pack that builds a count of assets found in Cloud computing environments.

## Prereqs

- [cnquery](https://cnquery.io) - Install cnquery locally

### Run AWS

Ensure you have API access to the AWS account you want to scan. 

```bash
cnquery scan aws -f aws-inventory.mql.yaml
```