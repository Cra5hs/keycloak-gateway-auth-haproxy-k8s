# Keycloak gateway authen infra with kubernetes
0. Required
    - Domain (You can buy from namecheap)
1. Infrastructure
    - Nginx ⚡
    - Postgre SQL HA ⚡
    - Keycloak ⚡

# How to use
1. Run 
 ```
 sh 99-deploy-cluster.sh
```
2. Point A Record from Domain to LoadBalancerIP generate from Kubernetes (NGINX Ingress)
3. Import ./keycloak/hotel-realm.json to keycloak (Keycloak -> Realm -> Create realm -> import file)

# Architecture

![sisox](https://github.com/Cra5hs/keycloak-gateway-auth/assets/5536388/dcf2df46-4ca9-466f-bbba-8177004e4f33)

