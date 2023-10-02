---

1)create argocd namespace

2) kubectl applay -f install -n argocd

3) kubectl get all -n argocd

4) kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d; echo (Get First Password )
