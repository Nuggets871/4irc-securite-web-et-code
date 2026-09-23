# 4IRC - Sécurité Web et Code

Cours de sécurité web et code (CPE Lyon).

La plateforme de challenge est disponible sur : https://dashbox.cloud/

## TP 2 - Stratégies d'authentification

1. Cloner le repo du TP dans le dossier `swc-tp-keycloak` :

```bash
git clone https://github.com/pierreavn/swc-tp-keycloak.git swc-tp-keycloak
```

2. Lancer l'application :

```bash
cd swc-tp-keycloak
docker compose up
```

3. Accéder aux services :

- Application : http://localhost:8081
- Console Keycloak : http://localhost:8080 (`admin` / `admin`)

> Si Keycloak redémarre en boucle (permissions sur `./keycloak-data`) :
> `sudo chown -R 1000:1000 ./keycloak-data`
