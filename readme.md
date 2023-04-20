## Question 3 : Compléter le schéma suivant avec des objets Kubernetes

![schema](./img-kubernetes.png)

## Question 4 : Builder et publier (à partir de l’image nginx) sur le DockerHub, une image docker pour chacun des sites web présent sur le schéma précédent. Vous devez avoir 3 images (une par magasin tacos, pizzas et burgers)

```bash
docker build -t william/pizza:1.0.0 .
docker tag william/pizza:1.0.0 william/pizza:1.0.0-release
docker push william/pizza:1.0.0-release
```

```bash
docker build -t william/burger:1.0.0 .
docker tag william/burger:1.0.0 william/burger:1.0.0-release
docker push william/burger:1.0.0-release
```

```bash
docker build -t william/tacos:1.0.0 .
docker tag william/tacos:1.0.0 william/tacos:1.0.0-release
docker push william/tacos:1.0.0-release
```
