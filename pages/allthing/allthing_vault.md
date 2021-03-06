---
title: Documentation 
last_updated: July xx, 2018
summary: "Summary"
series: "ACME series"
weight: 3
sidebar: allthing_sidebar
permalink: allthing_vault.html
folder: allthing
# Don't forget to add a reference in _data/sidebars/allthing_sidebar.yml and/or _data/topnav.yml 
---

### Use Vault for random number generation and hashing
https://www.vaultproject.io/api/system/tools.html

### How to use Vault's API (From CURL):
https://www.vaultproject.io/api/index.html

### How to work with policies and configuration
https://www.hashicorp.com/blog/codifying-vault-policies-and-configuration

### Where go gets its CAs from. This is particularly important in getting rabbit-mq working.
https://golang.org/src/crypto/x509/root_linux.go

### Alternatives to Vault
https://github.com/OpenVPN/easy-rsa

### AppRole authentication for Vault
https://blog.alanthatcher.io/vault-approle-authentication/

### Write documentation:
vaultproject.io/docs/commands/write.html

### How to generate tokens:
vaultproject.io/api/auth/token/#role_name

### How to communicate with Vault in python:
github.com/ianunruh/hvac

### Good Vault setup guide (Intermediate CA):
cuddletech.com/?p=959


### Another guide to setting up vault with an intermediate CA (openssl gened):
blog.kintoandar.com/2015/11/vault-PKI-made-easy.html
### Setting up Vault with kuberneties:
blog.digitalocean.com/vault-and-kubernetes
### Yet another vault setup guide:
gist.github.com/chrishoffman/acc60cf577e1e79f56beb63747466d3c
### Less good guide for setting up Vault. It uses an intermediate CA, but from an openssl gen:
werner-dijkerman.nl/2017/08/25/automatically-generate-certificates-with-vault

### Docs on Vault PKI (Includes intermediate CA):
vaultproject.io/docs/secrets/pki/index.html

### More basic guide to setting up vault:
hackernoon.com/vault-as-ca-with-pki-backend-bbcfc315f06f

### Using TLS certs as an auth method:
vaultproject.io/docs/auth/cert.html

### Vault with postgres as the backend:
cloudacademy.com/blog/hashicorp-vault-how-to-secure-secrets-inside-microservices

### Vault/Consol high availability autopilot pattern:
github.com/autopilotpattern/vault

### Other PKI solutions:
ask.cronweekly.com/d/19-deploying-an-internal-ca-looking-for-advice

### CFSSL good example:
nomadproject.io/guides/securing-nomad.html

{% include links.html %}
