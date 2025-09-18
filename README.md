# Helm deployment

```bash
helm upgrade --install postgres-db \
  "/c/Users/samue/Documents/SAMUEL/ForeachAcademy/MASTER/Projet Agence Furious Ducks/Code/Infra/furious-ducks-helm-charts" \
  --namespace postgres \
  -f /c/Users/samue/Documents/SAMUEL/Projet\ Perso/POC/services-products-workflow-api/postgresql/common.yaml \
  -f /c/Users/samue/Documents/SAMUEL/Projet\ Perso/POC/services-products-workflow-api/postgresql/dev.yaml \
  --wait --debug
```
