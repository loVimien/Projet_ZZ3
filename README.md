# Projet Evaluation de la surface d'attaque externe d'une société

## Clonage du dépot

```
git clone --recurse-submodules git@github.com:loVimien/Projet_ZZ3.git
```

## Construction des images

```
docker-compose build
```

## Déploiement

```
docker-compose up -d
```

## Suppression des conteneurs

```
docker-compose down
```

## Ajout de module

Mettre un hostname au conteneur (option --hostname de docker run), le déployer dans le réseau _project_ (option --network de docker run) puis voir https://github.com/loVimien/Projet_ZZ3_Backend pour ajouter le module à la liste du Back-end