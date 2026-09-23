# 4IRC - Sécurité Web et Code

Cours de sécurité web et code (CPE Lyon).

La plateforme de challenge est disponible sur : https://dashbox.cloud/

## TP 2 - Stratégies d'authentification

Application Flask + Keycloak fournie sur : https://github.com/pierreavn/swc-tp-keycloak

```bash
git clone https://github.com/pierreavn/swc-tp-keycloak.git
cd swc-tp-keycloak
docker compose up
```

- Application : http://localhost:8081
- Console Keycloak : http://localhost:8080 (`admin` / `admin`)

> Si Keycloak redémarre en boucle (erreur de permissions sur `./keycloak-data`) :
> `sudo chown -R 1000:1000 ./keycloak-data`
