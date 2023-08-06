# keycloak-gateway-auth-haproxy-k8s

keycloak-gateway-auth-haproxy-k8s is an authentication and authorization gateway for cloud native apps.

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
4. Source code frontend: app1.sisox.site & app2.sisox.site (https://github.com/Cra5hs/hotel-spa-demo)

# Architecture
![sisox (1)](https://github.com/Cra5hs/keycloak-gateway-auth/assets/5536388/7f25d924-2f12-4077-b006-0a7f7f4b55aa)
