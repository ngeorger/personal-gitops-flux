# personal-gitops-flux

```sh
  flux bootstrap github \
  --repository ngeorger/personal-gitops-flux --owner ngeorger \
  --personal \
  --path bootstrap \
  --author-email info@sredevops.cl \
  --context <your-context> \ #Default default 
  --token-auth \
  --read-write-key true \
  --reconcile true \
  --interval 1h
```

Based on: [Funky Penguin's Geek Cookbook](https://geek-cookbook.funkypenguin.co.nz/kubernetes)
