# provaldap
Prova ldap d'ASO 2019

## Per accedir als repositoris:
- GitHub: welharrak/provaldap
- DockerHub: welharrak/provaldap:2019 i welharrak/provaldap:latest

## Descripció

He creat una nova entitat amb base **dc=walid,dc=cat**, amb una Organizational Unit anomenada **Socis** on dintre he afegit 3 entitats/socis amb les seves dades
corresponents: idcat, sardanes, foto, lema i el seu twitter, aquestes dades perteneixen a indepeOrgPerson, un objectClass que he creat jo, un objectClass estructural i un subtipus d'inetOrgPerson. En aqusta base de dades tothom pot canviar les seves propies dades però no poden veure les dades dels altres.

Una vegada creada l'estructura i les entitats, he creat una nova objectClass, marchenaAccount, en aquest cas no depen de cap objectClass però es auxiliar, les seves dades son: delictes, anysComdemna i galeres. Aquestes dades les he afegit a dos socis privilegiats.
