Step 1. kubectl create ns bank

Step 2. kubectl -n bank apply -f jwt/jwt-secret.yaml

Step 3. Edit frontend-ingress.yaml if need

Step 4. kubectl -n bank apply -f .
