#on part d'une image préexistante
FROM postgres:14.1-alpine


# On copie les scripts d'initialisation dans le dossier dédié pour être exécutés au démarrage de la base de données
COPY /docker-entrypoint-initdb.d/* /docker-entrypoint-initdb.d/
