# Keycloak gateway authen infra with kubernetes
0. Required
    - Domain (You can buy from namecheap)
1. Infrastructure
    - Nginx ⚡

# How to use
1. Run 
 ```
 sh 99-deploy-cluster.sh
```
2. Point A Record from Domain to LoadBalancerIP generate from Kubernetes (NGINX Ingress)
3. Import ./keycloak/hotel-realm.json to keycloak (Keycloak -> Realm -> Create realm -> import file)
  
![sisox](https://github.com/Cra5hs/stock-trading-infra/assets/5536388/6adc8d32-d762-42ca-8341-ba151d5e517d)
