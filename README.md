# openfaas-oidc

Authenticate the faas-cli with GitHub Actions OIDC

[Learn more](https://actuated.dev/blog/oidc-proxy-for-openfaas)

```yaml
- uses: self-actuated/openfaas-oidc@v1
  with: 
    gateway: https://oidc-proxy.example.com

- name: Check OpenFaaS version
  run: |
    OPENFAAS_CONFIG=$HOME/.openfaas/
    faas-cli version
```
